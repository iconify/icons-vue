<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8qp8ueqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:navigation-line-sharp-fill" /></template>
<style>
.b8qp8ueqa {
  fill: currentColor;
  d: path("M11.931 8.41C12.259 8.46 12.756 8.7 12.901 9L18.902 21.57C19.072 21.93 19.016 22.35 18.761 22.65C18.505 22.95 18.097 23.07 17.719 22.96L11.999 21.28L6.28 22.96C5.902 23.07 5.493 22.95 5.238 22.65C4.983 22.35 4.928 21.93 5.098 21.57L11.097 9C11.224 8.73 11.655 8.49 11.931 8.41ZM12.999 1V7H10.999V1H12.999Z");
}

</style>
