<script setup lang="ts">

import ExtensionCard from "@/components/ExtensionCard.vue";
</script>

<template>
  <main>
    <img class="background" src="https://s1.ax1x.com/2023/05/22/p9okyfs.jpg" alt="">
    <div class="title">
      <h1>TurboWarp 第三方扩展</h1>
    </div>
    <main>
      <h2 class="category-title">投稿</h2>
      <section class="extensions">
        <ExtensionCard>
          <template v-slot:name>Recording</template>
          <template v-slot:author>-SPIC-</template>
          <template v-slot:desc>利用用户设备上的麦克风录制音频，并将录制的音频文件进行下载</template>
        </ExtensionCard>

        <ExtensionCard>
          <template v-slot:name>Consoles</template>
          <template v-slot:author>-SIPC-</template>
          <template v-slot:desc>用于控制和操作浏览器内置的JavaScript控制台</template>
        </ExtensionCard>

        <ExtensionCard>
          <template v-slot:name>Encoding</template>
          <template v-slot:author>-SIPC-</template>
          <template v-slot:desc>将字符串编码或解码为 Unicode,Base64,URL</template>
        </ExtensionCard>

        <ExtensionCard>
          <template v-slot:name>Time</template>
          <template v-slot:author>-SIPC-</template>
          <template v-slot:desc>用于与unix时间戳和其他日期字符串交互的块</template>
        </ExtensionCard>

        <ExtensionCard>
          <template v-slot:name>Temporaryvariables</template>
          <template v-slot:author>-SIPC-</template>
          <template v-slot:desc>在Scratch中实时创建,修改,删除变量</template>
        </ExtensionCard>

        <ExtensionCard>
          <template v-slot:name>rxFS</template>
          <template v-slot:author>0832</template>
          <template v-slot:desc>在Scratch中轻松地构建一个文件系统<br>实现管理,存储,访问数据功能</template>
        </ExtensionCard>

        <ExtensionCard>
          <template v-slot:name>json</template>
          <template v-slot:author>skyhigh173</template>
          <template v-slot:desc>用于对字符进行 JSON 格式的处理和转换<br>轻松地创建数组,解析JSON</template>
        </ExtensionCard>

        <ExtensionCard>
          <template v-slot:name>post-process</template>
          <template v-slot:author>LoserFox</template>
          <template v-slot:desc>用于对舞台进行色散、故障和其他视觉效果的操作</template>
        </ExtensionCard>

        <ExtensionCard>
          <template v-slot:name>ChatGPT</template>
          <template v-slot:author>zmh-program</template>
          <template v-slot:desc>允许用户调用 ChatGPT 模型进行自然语言对话</template>
        </ExtensionCard>

        <ExtensionCard>
          <template v-slot:name>bitwiseoper</template>
          <template v-slot:author>CK七星松</template>
          <template v-slot:desc>提供了多个位运算和位操作符<br>可以在编程和逻辑表达式中进行高级操作</template>
        </ExtensionCard>

        <ExtensionCard>
          <template v-slot:name>mathandgeom</template>
          <template v-slot:author>CK七星松</template>
          <template v-slot:desc>提供了丰富的数学运算和图形处理功能<br>适用于编程和数据可视化等领域</template>
        </ExtensionCard>

        <ExtensionCard>
          <template v-slot:name>numeration</template>
          <template v-slot:author>CK七星松</template>
          <template v-slot:desc>用于进行科学技术法的换算和转换<br>可以帮助用户进行数字的表示和转换</template>
        </ExtensionCard>

        <ExtensionCard>
          <template v-slot:name>strmani</template>
          <template v-slot:author>CK七星松</template>
          <template v-slot:desc>专门用于处理和操作字符串<br>对字符串进行分割、替换、合并、格式化等操作</template>
        </ExtensionCard>

        <!-- 更多扩展 -->
      </section>
    </main>
    <footer class="section" style="text-align:center;">
      <div class="links">
        <a href="http://qm.qq.com/cgi-bin/qm/qr?_wv=1027&k=Hgd2J7dxazSx1QE462aKjLi5CXcm5U4G&authKey=Vb%2FA%2BFamtI97LgQkc3LWA0bE%2Bc1W1%2FonuAqfrtaZNRmz3Ia%2Fks%2Bfbd37UPd81xn1&noverify=0&group_code=770741679">提交你的扩展</a>
      </div>
    </footer>
  </main>
</template>

<style scoped>
main {
  display: flex;
  flex-direction: column;
}
.background {
  width: 100%;
  object-fit: cover;
  position: absolute;
  z-index: -1;
}
.title {
  padding: 40px 45px;
  width: max-content;
  background: rgba(255,255,255,.1);
  backdrop-filter: blur(5px);
  border-radius: 10px;
  margin: 18px auto;
  color: #fff;
  font-weight: bold !important;
  transition: .25s ease-in;
}

.title:hover {
  background: rgba(255,255,255,.2);
}
</style>
