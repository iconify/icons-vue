<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klahzjslt"/><path class="vr60o2_9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-add-home-work" /></template>
<style>
.klahzjslt {
  fill: currentColor;
  d: path("M11 14H5v5H3v-6.97l5-3.57l5 3.57v1.08c.57-.59 1.25-1.07 2-1.42V11L8 6l-7 5v10h6v-5h2v5h2.68c-.43-.91-.68-1.92-.68-3zm6-7h2v2h-2z");
}

.vr60o2_9k {
  fill: currentColor;
  d: path("M23 13.11V3H10v1.97l2 1.43V5h9v6.68c.75.36 1.43.84 2 1.43M23 18c0-2.76-2.24-5-5-5s-5 2.24-5 5s2.24 5 5 5s5-2.24 5-5m-5.5 3v-2.5H15v-1h2.5V15h1v2.5H21v1h-2.5V21z");
}

</style>
