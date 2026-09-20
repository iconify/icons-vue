<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_pejqv6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-hand-sharp" /></template>
<style>
.c_pejqv6c {
  fill: currentColor;
  d: path("M5 21V3h11.077v2.135h-2.616v7.602l-3.438-1.7l-3.357 3.492L11.785 21zm10.777 0q-.43 0-.814-.159q-.384-.158-.66-.508l-4.476-5.64l.712-.75l5.307 2.615V7.519h.923l3 3V18q0 1.25-.875 2.125T16.77 21zM11.078 7.078q.23-.23.23-.54T11.078 6t-.54-.23T10 6t-.23.54q0 .309.23.539t.54.23t.539-.23");
}

</style>
