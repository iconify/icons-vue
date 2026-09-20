<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r6tko4bxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vehicle-car-32-filled" /></template>
<style>
.r6tko4bxq {
  fill: currentColor;
  d: path("M6.502 6.132A4 4 0 0 1 10.406 3h11.187a4 4 0 0 1 3.905 3.132L26.135 9H27a1 1 0 1 1 0 2h-.42l.33 1.485A4 4 0 0 1 29 16v10a3 3 0 0 1-3 3h-1a3 3 0 0 1-3-3v-1H10v1a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V16a4 4 0 0 1 2.09-3.515L5.42 11H5a1 1 0 1 1 0-2h.864zM7.247 12h17.506l-1.207-5.434A2 2 0 0 0 21.593 5H10.407a2 2 0 0 0-1.953 1.566zM5 25v1a1 1 0 0 0 1 1h1a1 1 0 0 0 1-1v-1zm19 0v1a1 1 0 0 0 1 1h1a1 1 0 0 0 1-1v-1zm-11.5-5a1 1 0 0 0 1 1h5a1 1 0 1 0 0-2h-5a1 1 0 0 0-1 1m-3-1a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3M24 17.5a1.5 1.5 0 1 0-3 0a1.5 1.5 0 0 0 3 0");
}

</style>
