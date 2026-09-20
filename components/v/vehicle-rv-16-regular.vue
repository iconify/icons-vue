<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oaxmy-bjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vehicle-rv-16-regular" /></template>
<style>
.oaxmy-bjh {
  fill: currentColor;
  d: path("M12.616 2.009a1.75 1.75 0 0 1 1.572 1.741V5a1 1 0 0 1-1 1h-.38l1.057 2.113A1.75 1.75 0 0 1 15 9.75v1.5A1.75 1.75 0 0 1 13.25 13h-.52a1.998 1.998 0 0 1-3.46 0H6.73a1.998 1.998 0 0 1-3.46 0h-.52A1.75 1.75 0 0 1 1 11.25v-7.5C1 2.784 1.784 2 2.75 2h9.688zM5 11a1 1 0 1 0 0 2a1 1 0 0 0 0-2m6 0a1 1 0 1 0 0 2a1 1 0 0 0 0-2m-9 .25c0 .414.336.75.75.75H3a2 2 0 1 1 4 0h2a2 2 0 1 1 4 0h.25a.75.75 0 0 0 .75-.75v-1.5a.75.75 0 0 0-.75-.75H2zM2.75 3a.75.75 0 0 0-.75.75V8h6V6.75C8 5.784 8.784 5 9.75 5h3.438V3.75a.75.75 0 0 0-.673-.746L12.437 3zm7 3a.75.75 0 0 0-.75.75V8h3.691l-1-2zM6.103 4.005A1 1 0 0 1 7 5v1a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h2zM4 6h2V5H4z");
}

</style>
