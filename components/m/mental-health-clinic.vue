<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqs969t5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mental-health-clinic" /></template>
<style>
.aqs969t5o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.979 8.133l5.875-4.838q2.146-1.768 4.292 0l5.875 4.838q1.23 1.013 1.229 2.606v7.636q0 3.375-3.375 3.375H6.125q-3.375 0-3.375-3.375v-7.636q-.001-1.593 1.229-2.606M12 8.177q-.719-.585-1.995-.487q-1.862.143-2.187 1.625q-1.392.286-1.905 1.823q-.472 1.417.184 2.434q-.575 1.212.06 2.355q.735 1.323 2.343 1.323h2.75v1q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T12 19t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-1h2.75q1.608 0 2.343-1.323q.635-1.143.06-2.355q.656-1.017.184-2.434q-.513-1.537-1.905-1.823q-.325-1.482-2.187-1.625q-1.276-.098-1.995.487");
}

</style>
