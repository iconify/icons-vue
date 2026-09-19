<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rae0znb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:techmino" /></template>
<style>
.rae0znb6j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.112 6.325l-1.769-.474L4.5 16.462l1.769.474m9.711-8.771l1.768.474l-2.843 10.611l-1.769-.474m10.852-8.465l-1.769-.474l-2.843 10.611l1.768.474m9.711-8.771l1.769.474l-2.843 10.611l-1.769-.474m-8.024 2.476l-1.769-.474l-2.843 10.611l1.769.474m9.711-8.771l1.768.474l-2.843 10.611l-1.769-.474m10.852-8.465l-1.769-.474l-2.843 10.611l1.768.474m9.711-8.771l1.769.474l-2.843 10.611l-1.769-.474");
}

</style>
