<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yiabw_bxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shapes-outline-sharp" /></template>
<style>
.yiabw_bxa {
  fill: currentColor;
  d: path("M8 17.95q.25.025.488.038T9 18t.513-.012t.487-.038V20h10V10h-2.05q.025-.25.038-.488T18 9t-.012-.513T17.95 8H22v14H8zm-3.962-3.987Q2 11.925 2 9t2.038-4.962T9 2t4.963 2.038T16 9t-2.037 4.963T9 16t-4.962-2.037m8.5-1.425Q14 11.075 14 9t-1.463-3.537T9 4T5.463 5.463T4 9t1.463 3.538T9 14t3.538-1.463M9 9");
}

</style>
