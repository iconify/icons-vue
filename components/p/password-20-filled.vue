<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mpap8jb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:password-20-filled" /></template>
<style>
.mpap8jb9j {
  fill: currentColor;
  d: path("M2 6.75A2.75 2.75 0 0 1 4.75 4h10.5A2.75 2.75 0 0 1 18 6.75v5.5A2.75 2.75 0 0 1 15.25 15H4.75A2.75 2.75 0 0 1 2 12.25zm5.146 1.396l-.646.647l-.646-.647a.5.5 0 1 0-.708.708l.647.646l-.647.646a.5.5 0 0 0 .708.708l.646-.647l.646.647a.5.5 0 0 0 .708-.708L7.207 9.5l.647-.646a.5.5 0 1 0-.708-.708m4 0l-.646.647l-.646-.647a.5.5 0 1 0-.708.708l.647.646l-.647.646a.5.5 0 0 0 .708.708l.646-.647l.646.647a.5.5 0 0 0 .708-.708l-.647-.646l.647-.646a.5.5 0 0 0-.708-.708M13 10.5a.5.5 0 0 0 .5.5h2a.5.5 0 0 0 0-1h-2a.5.5 0 0 0-.5.5");
}

</style>
