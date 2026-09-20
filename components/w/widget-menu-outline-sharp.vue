<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezy7icbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:widget-menu-outline-sharp" /></template>
<style>
.ezy7icbwv {
  fill: currentColor;
  d: path("M8.942 17.192q.881 0 1.508-.626q.627-.627.627-1.508t-.627-1.508t-1.508-.627t-1.508.627q-.626.627-.626 1.508t.626 1.508t1.508.626m6.097 0q.88 0 1.507-.626q.627-.627.627-1.508t-.627-1.508t-1.507-.627t-1.508.627t-.627 1.508t.627 1.508t1.508.626m-6.087-1q-.463 0-.804-.34q-.34-.34-.34-.794q0-.473.34-.804t.794-.331q.473 0 .804.33t.331.795t-.33.804q-.332.34-.795.34m6.096 0q-.463 0-.804-.34q-.34-.34-.34-.794q0-.473.34-.804t.795-.331q.473 0 .803.33t.331.795t-.33.804q-.332.34-.795.34m-6.337-5.557h6.558q.8 0 1.352-.552q.552-.553.552-1.352t-.552-1.352t-1.352-.552H8.711q-.799 0-1.351.552t-.552 1.352t.552 1.352t1.351.552m0-1q-.373 0-.638-.266q-.265-.265-.265-.638t.265-.639t.638-.265h6.558q.373 0 .639.265q.265.266.265.639t-.265.638t-.639.266zM4 20V4h16v16zm1-1h14V5H5zm0 0V5z");
}

</style>
