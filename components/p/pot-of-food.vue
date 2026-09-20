<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="hdkdu3p1m"/><path class="ohn67sbok"/><ellipse class="hhh5x833g"/><path class="fu36g-pkv"/><path class="hp3jggs0l"/><path class="oiiemr8ws"/><path class="z4k9mfbha"/><path class="lavzj6h1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:pot-of-food" /></template>
<style>
.fu36g-pkv {
  fill: var(--svg-color--77b255, #77b255);
  d: path("M4 16c-.542-2.169 2-6 7-5c1-1 2.838-2 6-2c2 0 5.612 1.775 4 5c-1 2-5 5-10 3c-1 1-6 3-7-1");
}

.hdkdu3p1m {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M13.037 34.816C.794 33.013 1 20.719 1 17h34c0 1.914.087 15.77-13.125 17.918c-2.042.332-6.458.249-8.838-.102");
}

.hhh5x833g {
  cx: 18px;
  cy: 18px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  rx: 15px;
  ry: 7px;
}

.hp3jggs0l {
  fill: var(--svg-color--5c913b, #5c913b);
  d: path("M12 17c-.249.036-.471.073-.678.111C16.17 18.857 20.022 15.956 21 14c1.078-2.156-.181-3.66-1.731-4.423c.394 1.822-1.128 6.546-7.269 7.423");
}

.lavzj6h1y {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("M27 19.001c-.209 0-.423-.034-.633-.104l-3-1a2 2 0 0 1 1.265-3.795l3 1A2 2 0 0 1 27 19.001M26 22h-2a1 1 0 1 1 0-2h2a1 1 0 1 1 0 2");
}

.ohn67sbok {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M33.388 13.247c2.467-5.574-8.331-5.254-11.035-4.382A38 38 0 0 0 18 8.611c-9.389 0-17 3.228-17 8.444c0 1.009.291 1.979.818 2.891c-4.327 5.712 4.246 6.786 9.184 5.71c2.136.537 4.5.844 6.998.844c9.389 0 17-4.229 17-9.444c0-1.43-.589-2.704-1.612-3.809");
}

.oiiemr8ws {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M5 16c.525-1.313 5-3 10 3c1 1 4.586 1.586 6 3c1 1 0 2-4 2S3 21 5 16");
}

.z4k9mfbha {
  fill: var(--svg-color--b27962, #b27962);
  d: path("M6.041 20.018C8.589 22.561 14.231 24 17 24c4 0 5-1 4-2c-.326-.326-.77-.607-1.268-.86c-3.204 1.733-11.68-.144-13.691-1.122");
}

</style>
