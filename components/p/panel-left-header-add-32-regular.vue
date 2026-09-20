<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k7elcdbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-left-header-add-32-regular" /></template>
<style>
.k7elcdbwc {
  fill: currentColor;
  d: path("M12 13v13h2.512c.252.712.59 1.383 1.003 2H6.5A4.5 4.5 0 0 1 2 23.5v-15A4.5 4.5 0 0 1 6.5 4h19A4.5 4.5 0 0 1 30 8.5v8.843a9 9 0 0 0-2-1.828V13zm0-2h16V8.5A2.5 2.5 0 0 0 25.5 6H12zm-2-5H6.5A2.5 2.5 0 0 0 4 8.5v15A2.5 2.5 0 0 0 6.5 26H10zm20.5 17a7.5 7.5 0 1 1-15 0a7.5 7.5 0 0 1 15 0M24 18.25a.75.75 0 0 0-1.5 0V22h-3.75a.75.75 0 0 0 0 1.5h3.75v3.75a.75.75 0 0 0 1.5 0V23.5h3.75a.75.75 0 0 0 0-1.5H24z");
}

</style>
