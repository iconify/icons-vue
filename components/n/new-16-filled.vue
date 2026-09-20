<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="st0j9fbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:new-16-filled" /></template>
<style>
.st0j9fbxk {
  fill: currentColor;
  d: path("M3.75 10.999h4.5a.75.75 0 0 1 .102 1.493l-.102.007h-4.5a.75.75 0 0 1-.102-1.493zh4.5zm1.47-5.78a.75.75 0 0 1 .976-.072l.084.073l3.5 3.5a.75.75 0 0 1-.976 1.133L8.72 9.78l-3.5-3.5a.75.75 0 0 1 0-1.06M11.75 3a.75.75 0 0 1 .743.648l.007.102v4.5a.75.75 0 0 1-1.493.102L11 8.25v-4.5a.75.75 0 0 1 .75-.75");
}

</style>
