<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9ygskbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:turn-left-outline" /></template>
<style>
.z9ygskbif {
  fill: currentColor;
  d: path("M15.52 19v-7.884q0-.27-.174-.443q-.173-.173-.442-.173H5.916l2.1 2.1l-.708.708L4 10l3.308-3.308l.708.708l-2.1 2.1h8.988q.671 0 1.143.472t.472 1.144V19z");
}

</style>
