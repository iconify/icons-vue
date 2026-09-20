<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hf581nf8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:water-full-sharp" /></template>
<style>
.hf581nf8d {
  fill: currentColor;
  d: path("M5.68 8.933Q6.938 8.219 8.3 7.86q1.363-.36 2.788-.36q.73 0 1.458.09t1.434.29q1.327.37 2.018.495q.692.125 1.5.125h.886l.483-4.5H5.116zM6.028 21L4 3h16l-2.008 18z");
}

</style>
