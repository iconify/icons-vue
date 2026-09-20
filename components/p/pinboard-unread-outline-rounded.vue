<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfp03et_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pinboard-unread-outline-rounded" /></template>
<style>
.vfp03et_x {
  fill: currentColor;
  d: path("M15.73 7.272Q15 6.543 15 5.502t.729-1.771T17.498 3t1.771.729T20 5.498t-.728 1.771t-1.77.731t-1.771-.728M13.042 6H3.5q-.213 0-.356-.144T3 5.499t.144-.356T3.5 5h9.542q-.011.116-.026.238q-.016.12-.016.252t.016.253t.026.257m-.1 13q-.212 0-.356-.144t-.144-.357t.144-.356t.356-.143h6.443q.269 0 .442-.173t.173-.442V9.21q.292-.18.545-.39T21 8.346v9.039q0 .69-.462 1.153T19.385 19zm-6.491 1.856q-.143-.144-.143-.356v-4.27H3.787q-.46 0-.696-.384q-.237-.384-.02-.788l1.352-2.689V9.385H3.5q-.213 0-.356-.144Q3 9.097 3 8.884t.144-.356t.356-.144h6.616q.212 0 .356.145t.144.356t-.144.356t-.356.144h-.924v2.984l1.352 2.689q.218.404-.019.788q-.236.385-.696.385H7.308V20.5q0 .213-.144.356T6.807 21t-.356-.144m-2.305-5.625H9.47l-1.277-2.543V9.385h-2.77v3.304zm2.662 0");
}

</style>
