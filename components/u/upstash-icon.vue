<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":341};
const content = `<path class="w2ua6wb4v"/><path class="hel2wrbms"/><path class="kevo0xbxb"/><path class="sqe2gfa0u"/><path class="xpd42gb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:upstash-icon" /></template>
<style>
.hel2wrbms {
  fill: var(--svg-color--00c98d, #00c98d);
  d: path("M51.2 247.216c28.277 28.277 74.123 28.277 102.4 0c28.277-28.276 28.277-74.123 0-102.4l-25.6 25.6c14.14 14.138 14.14 37.061 0 51.2c-14.138 14.139-37.061 14.139-51.2 0zM256 42.415c-56.554-56.553-148.247-56.553-204.8 0c-56.555 56.555-56.555 148.247 0 204.801l25.599-25.6c-42.415-42.415-42.415-111.185 0-153.6c42.416-42.416 111.185-42.416 153.6 0z");
}

.kevo0xbxb {
  fill: var(--svg-color--00c98d, #00c98d);
  d: path("M204.8 93.616c-28.276-28.277-74.124-28.277-102.4 0c-28.278 28.277-28.278 74.123 0 102.4l25.6-25.6c-14.14-14.138-14.14-37.061 0-51.2c14.138-14.139 37.06-14.139 51.2 0z");
}

.sqe2gfa0u {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M256 42.415c-56.554-56.553-148.247-56.553-204.8 0c-56.555 56.555-56.555 148.247 0 204.801l25.599-25.6c-42.415-42.415-42.415-111.185 0-153.6c42.416-42.416 111.185-42.416 153.6 0z");
}

.w2ua6wb4v {
  fill: var(--svg-color--00c98d, #00c98d);
  d: path("M0 298.417c56.554 56.553 148.247 56.553 204.801 0c56.554-56.554 56.554-148.247 0-204.801l-25.6 25.6c42.415 42.416 42.415 111.185 0 153.6c-42.416 42.416-111.185 42.416-153.601 0z");
}

.xpd42gb0r {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M204.8 93.616c-28.276-28.277-74.124-28.277-102.4 0c-28.278 28.277-28.278 74.123 0 102.4l25.6-25.6c-14.14-14.138-14.14-37.061 0-51.2c14.138-14.139 37.06-14.139 51.2 0z");
}

</style>
