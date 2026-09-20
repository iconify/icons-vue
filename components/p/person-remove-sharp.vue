<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytnupogkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:person-remove-sharp" /></template>
<style>
.ytnupogkx {
  fill: currentColor;
  d: path("M16 11V9h6v2zm-9.825-.175Q5 9.65 5 8t1.175-2.825T9 4t2.825 1.175T13 8t-1.175 2.825T9 12t-2.825-1.175M1 20v-2.8q0-.85.438-1.562T2.6 14.55q1.55-.775 3.15-1.162T9 13t3.25.388t3.15 1.162q.725.375 1.163 1.088T17 17.2V20z");
}

</style>
