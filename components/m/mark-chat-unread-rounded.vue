<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qaurl3bry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mark-chat-unread-rounded" /></template>
<style>
.qaurl3bry {
  fill: currentColor;
  d: path("M16.875 5.125Q16 4.25 16 3t.875-2.125T19 0t2.125.875T22 3t-.875 2.125T19 6t-2.125-.875M6 18l-2.3 2.3q-.475.475-1.088.213T2 19.575V4q0-.825.588-1.412T4 2h9.1q.4 0 .663.3T14 3q0 1.125.488 2.125T15.85 6.85q.65.525 1.463.838T19 8q.45 0 .9-.075t.875-.25t.825.05t.4.65V16q0 .825-.588 1.413T20 18z");
}

</style>
