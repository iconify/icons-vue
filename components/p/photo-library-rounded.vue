<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uy48eebek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:photo-library-rounded" /></template>
<style>
.uy48eebek {
  fill: currentColor;
  d: path("M9.154 13.692h8.692l-2.758-3.653l-2.453 3.077l-1.589-1.885zM8.116 17q-.691 0-1.153-.462T6.5 15.385V4.615q0-.69.463-1.153T8.116 3h10.769q.69 0 1.153.462t.462 1.153v10.77q0 .69-.462 1.152T18.884 17zm0-1h10.769q.23 0 .423-.192t.192-.423V4.615q0-.23-.192-.423T18.884 4H8.116q-.231 0-.424.192t-.192.423v10.77q0 .23.192.423t.423.192m-3 4q-.69 0-1.153-.462T3.5 18.385V6.615h1v11.77q0 .23.192.423t.423.192h11.77v1zm3-16h10.77q.23 0 .423.192t.192.423v10.77q0 .23-.192.423t-.424.192H8.116q-.231 0-.424-.192t-.192-.423V4.615q0-.23.192-.423T8.115 4");
}

</style>
