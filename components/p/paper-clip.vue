<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzn78j2eg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:paper-clip" /></template>
<style>
.yzn78j2eg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.25 8v8.5q0 2.175-1.538 3.712Q14.175 21.75 12 21.75t-3.712-1.538Q6.75 18.675 6.75 16.5V6q0-3.75 3.75-3.75T14.25 6v9q0 2.25-2.25 2.25T9.75 15V8.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146V15q0 .75.75.75t.75-.75V6q0-2.25-2.25-2.25T8.25 6v10.5q0 3.75 3.75 3.75t3.75-3.75V8q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
