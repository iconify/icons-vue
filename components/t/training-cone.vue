<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qy5cyyhff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:training-cone" /></template>
<style>
.qy5cyyhff {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.906 13.357Q2.25 14.579 2.25 17q0 3.25 9.75 3.25T21.75 17q0-2.421-5.656-3.643L14.47 7.79q-.017-.058-.043-.113q-.026-.054-.06-.104q-.035-.05-.077-.093q-.042-.044-.09-.08t-.102-.064t-.111-.048q-.057-.019-.117-.028t-.12-.01h-3.5q-.06 0-.12.01q-.06.009-.117.028t-.111.048q-.054.028-.102.064t-.09.08t-.077.093t-.06.104t-.043.113zm6.844-2.607q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-5.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T8.5 11.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
