<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="f6hv96bhk"/><path class="g5dgiibef"/><path class="s106jwbsi"/><path class="uft0dvnbc"/><ellipse transform="rotate(-46.196 18.814 17.86)" class="hphrzz2vm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ruby" /></template>
<style>
.f6hv96bhk {
  d: path("M32.035 33.12c-.03-.33-4.554-15.34-4.554-15.34l14.115-.49l-11.159-8.455l6.29-3.09M32.035 33.12l-14.77-5.453l-4.049 14.63l-5.042-13.342l-2.556 6.123");
}

.g5dgiibef {
  d: path("M13.102 42.376c9.92-4.07 26.7-7.791 29.332-30.306m.001 0c.572-6.434-2.727-6.285-5.483-6.47m0 0l-10.46.227");
}

.hphrzz2vm {
  cx: 18.814px;
  cy: 17.861px;
  rx: 15.372px;
  ry: 6.751px;
}

.s106jwbsi {
  d: path("m32.216 33.124l8.477 7.64c-.012-.173 1.686-28.396 1.686-28.396");
}

.uft0dvnbc {
  d: path("m38.526 25.365l2.167 15.4l-27.397 1.596m27.397-1.596l-19.058-1.709m-8.533 3.32c-6.68.304-8.004-2.396-7.508-7.385L7.14 25.37");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
