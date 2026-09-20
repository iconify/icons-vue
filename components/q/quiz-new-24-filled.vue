<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzs5swbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:quiz-new-24-filled" /></template>
<style>
.uzs5swbgs {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m0 1.999a.5.5 0 0 0-.5.5V17h-2.505a.5.5 0 0 0 0 1h2.506v2.504a.5.5 0 0 0 1 0V18h2.496a.5.5 0 0 0 0-1H18v-2.501a.5.5 0 0 0-.5-.5M17.75 3A3.25 3.25 0 0 1 21 6.25v5.774A6.47 6.47 0 0 0 17.5 11c-2.08 0-3.931.978-5.121 2.499H6.75a.75.75 0 0 0 0 1.5h4.749a6.5 6.5 0 0 0-.422 1.501H6.75a.75.75 0 0 0 0 1.5h4.272c.083 1.1.44 2.121 1.002 3H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3zM10 4.996a.75.75 0 0 0-.694.467l-2.25 5.502a.75.75 0 0 0 1.388.568l.424-1.036h2.262l.423 1.035a.75.75 0 0 0 1.388-.566l-2.247-5.503A.75.75 0 0 0 10 4.996m5.75 0a.75.75 0 0 0-.75.75v1.25h-1.25a.75.75 0 0 0 0 1.5H15v1.25a.75.75 0 0 0 1.5 0v-1.25h1.25a.75.75 0 0 0 0-1.5H16.5v-1.25a.75.75 0 0 0-.75-.75m-5.232 4.001H9.48L10 7.73z");
}

</style>
