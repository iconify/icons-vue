<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":269};
const content = `<defs><path id="SVGfwK6MdXe" class="wj20m6bde"/></defs><mask id="SVGSW7eXdBB" class="n1mjunbsu"><use href="#SVGfwK6MdXe"/></mask><use href="#SVGfwK6MdXe" class="iannhpbhy"/><path mask="url(#SVGSW7eXdBB)" class="fpqz0_bcm"/><path mask="url(#SVGSW7eXdBB)" class="o5l0882nu"/><path mask="url(#SVGSW7eXdBB)" class="gz9wv8brx"/><path mask="url(#SVGSW7eXdBB)" class="n7bhw-bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:unitjs" /></template>
<style>
.fpqz0_bcm {
  fill: var(--svg-color--62655d, #62655d);
  d: path("m35.577 73.823l104.212-60.167L244 73.823v120.333l-104.211 60.166l-104.212-60.166z");
}

.gz9wv8brx {
  fill: var(--svg-color--a4d43a, #a4d43a);
  d: path("m139.789 0l-2.48 1.431v20.63l2.88-1.663l98.372 56.796v113.591l-98.372 56.795l-98.373-56.795v-56.796h24.579L33.197 77.194L0 133.989h23.577v67.295l116.212 67.095L256 201.284V67.095z");
}

.iannhpbhy {
  fill: var(--svg-color--a4d43a, #a4d43a);
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.n7bhw-bqo {
  fill: var(--svg-color--f7f7f7, #f7f7f7);
  d: path("m78.327 139.189l47.729-19.998s10.092 34.155 15.199 40.263c42.93-65.728 83.46-81.06 83.46-81.06v51.196s-40.216 20.477-87.46 72.527c-25.664-45.129-58.928-62.928-58.928-62.928");
}

.o5l0882nu {
  fill: var(--svg-color--3f4238, #3f4238);
  d: path("M139.789 20.398L41.416 77.194v113.591l98.373 56.795z");
}

.wj20m6bde {
  d: path("m139.789 0l-2.48 1.431V21.83L41.416 77.194v14.061l-8.219-14.061L0 133.989h23.577v67.295l116.212 67.095L256 201.284V67.095z");
}

</style>
