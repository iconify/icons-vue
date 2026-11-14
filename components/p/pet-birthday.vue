<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5c2pzhmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pet-birthday" /></template>
<style>
.y5c2pzhmr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.53 1.97q1.72 1.719 1.72 2.53q0 2.25-2.25 2.25T9.75 4.5q0-.811 1.72-2.53q.105-.106.243-.163T12 1.75t.287.057t.243.163m.22 6.78v2h3q3 0 3 3q0 .879-.258 1.501q3.258.058 3.258 3.374v.25q0 3.375-3.375 3.375H5.625q-1.398 0-2.386-.989q-.989-.988-.989-2.386v-.25q0-1.398.989-2.386q.946-.947 2.269-.987q-.258-.622-.258-1.502q0-1.243.879-2.121q.878-.879 2.121-.879h3v-2q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T12 8t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
