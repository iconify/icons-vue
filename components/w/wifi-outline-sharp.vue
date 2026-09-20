<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmthxs55n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wifi-outline-sharp" /></template>
<style>
.mmthxs55n {
  fill: currentColor;
  d: path("m6.35 15.35l-1.023-1.034q1.339-1.339 3.06-2.058q1.72-.72 3.613-.72t3.616.723q1.725.722 3.057 2.066L17.65 15.35q-1.125-1.125-2.587-1.737T12 13t-3.062.613T6.35 15.35M2.1 11.1l-1.023-1.023Q3.26 7.883 6.084 6.711T12 5.538t5.916 1.172t5.007 3.367L21.9 11.1q-1.975-1.975-4.537-3.037T12 7T6.637 8.063T2.1 11.1M12 21l-2.448-2.454q.489-.488 1.122-.748t1.326-.26t1.326.26q.634.26 1.122.748z");
}

</style>
