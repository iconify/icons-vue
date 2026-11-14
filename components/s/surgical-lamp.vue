<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojskh7fpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:surgical-lamp" /></template>
<style>
.ojskh7fpi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 2.5v5.25H14q3.003 0 5.127 2.123T21.25 15t-2.123 5.127T14 22.25t-5.127-2.123T6.75 15t2.123-5.127q.339-.338.7-.623H4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q3.25 8.574 3.25 8.5v-6q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q3.926 1.75 4 1.75t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146M12 12.75q0 2 2 2t2-2t-2-2t-2 2m-.25 1.75q-2 0-2 2t2 2q.828 0 1.414-.586t.586-1.414t-.586-1.414t-1.414-.586m2.5 2q0 2 2 2t2-2t-2-2t-2 2");
}

</style>
