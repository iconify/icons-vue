<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="g3c3cob3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:paint-brush-subtract-28-filled" /></template>
<style>
.g3c3cob3o {
  fill: currentColor;
  d: path("M17 6.25a.75.75 0 0 1-1.5 0V2H6.75a.75.75 0 0 0-.75.75V13h16V2.75a.75.75 0 0 0-.75-.75H20v6.25a.75.75 0 0 1-1.5 0V2H17zM13 20.5a7.49 7.49 0 0 1 3-6H6v1.75A2.75 2.75 0 0 0 8.75 19H11v4a3 3 0 0 0 4.16 2.767A7.48 7.48 0 0 1 13 20.5m7.5 6.5a6.5 6.5 0 1 0 0-13a6.5 6.5 0 0 0 0 13M16 20.5a.5.5 0 0 1 .5-.5h8a.5.5 0 0 1 0 1h-8a.5.5 0 0 1-.5-.5");
}

</style>
