<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea4ftv_re"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:photo-gallery-property" /></template>
<style>
.ea4ftv_re {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.25 18.75v.125q0 3.375-3.375 3.375H5.125q-3.375 0-3.375-3.375v-9.25q0-1.398.989-2.386q.853-.854 2.011-.97V5.5q0-2.25 2.25-2.25h13q2.25 0 2.25 2.25v11q0 2.25-2.25 2.25zm-13-12.5V5.5q0-.75.75-.75h13q.75 0 .75.75v11q0 .75-.75.75h-.75V9.625q0-3.375-3.375-3.375zm3.752 3.689l-4.5 4q-.017.015-.032.031q-.106.105-.163.243t-.057.287v4q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h9q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4q0-.161-.066-.307q-.066-.147-.186-.254l-4.5-4q-.051-.045-.109-.08t-.122-.06q-.064-.024-.132-.037q-.067-.012-.135-.012t-.135.012t-.132.037q-.063.024-.122.06t-.109.08M6.75 14.837v2.913h7.5v-2.913l-3.75-3.334z");
}

</style>
