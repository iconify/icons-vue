<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v38t8obsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sync-saved-locally-off-outline-sharp" /></template>
<style>
.v38t8obsd {
  fill: currentColor;
  d: path("m20.123 17.273l-.85-.85H20V5.462H8.312l-1-1H21v12.811zm1.07 5.335l-3.147-3.146H1.77v-1h15.272l-1-1H3V5.042h.615L1.392 2.808L2.1 2.1l19.8 19.8zm-6.158-6.146L4.48 5.902H4v10.56zm-1.939-6.235l2.079-2.079l.714.714l-2.098 2.079z");
}

</style>
