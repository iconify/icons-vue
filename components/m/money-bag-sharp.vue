<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ne5b2rv0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:money-bag-sharp" /></template>
<style>
.ne5b2rv0a {
  fill: currentColor;
  d: path("M12 16q-.825 0-1.412-.587T10 14t.588-1.412T12 12t1.413.588T14 14t-.587 1.413T12 16M7.375 7h9.25l2-4H5.375zM8.4 21h7.2q2.25 0 3.825-1.562T21 15.6q0-.95-.325-1.85t-.925-1.625L17.15 9H6.85l-2.6 3.125q-.6.725-.925 1.625T3 15.6q0 2.275 1.563 3.838T8.4 21");
}

</style>
