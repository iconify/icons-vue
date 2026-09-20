<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8fmzqkta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:traffic-outline-sharp" /></template>
<style>
.u8fmzqkta {
  fill: currentColor;
  d: path("M13.075 17.575q.425-.425.425-1.075t-.425-1.075T12 15t-1.075.425T10.5 16.5t.425 1.075T12 18t1.075-.425m0-4.5Q13.5 12.65 13.5 12t-.425-1.075T12 10.5t-1.075.425T10.5 12t.425 1.075T12 13.5t1.075-.425m0-4.5Q13.5 8.15 13.5 7.5t-.425-1.075T12 6t-1.075.425T10.5 7.5t.425 1.075T12 9t1.075-.425M7 21v-2.15q-1.275-.35-2.137-1.4T4 15h3v-1.15q-1.275-.35-2.137-1.4T4 10h3V8.85q-1.275-.35-2.137-1.4T4 5h3V3h10v2h3q0 1.4-.862 2.45T17 8.85V10h3q0 1.4-.862 2.45T17 13.85V15h3q0 1.4-.862 2.45T17 18.85V21zm2-2h6V5H9zm0 0V5z");
}

</style>
