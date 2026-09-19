<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vc-ay_brz"/><circle class="evlwmqbqo"/><circle class="m0w-ydb2y"/><circle class="j5v5djbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:super-cycle" /></template>
<style>
.evlwmqbqo {
  cx: 35.461px;
  cy: 34.501px;
  r: 7.384px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j5v5djbus {
  cx: 30.905px;
  cy: 14.236px;
  r: 3.378px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m0w-ydb2y {
  cx: 13.229px;
  cy: 34.501px;
  r: 7.384px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vc-ay_brz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.756 15.918c0-.488-7.412-7.37-7.938-7.37c-.277 0-.616.426-.754.947l-.25.948l-1.872-1.197c-1.03-.658-2.278-1.544-2.776-1.969s-.983-.698-1.08-.606c-.478.454-2.175 5.537-1.927 5.773c.321.304 8.3 2.989 8.882 2.989c.205 0 .466-.34.58-.755c.202-.73.27-.735 2.14-.13c1.061.344 2.394.855 2.96 1.135c1.135.563 2.035.667 2.035.235m1.231 21.969c.662-.662.721-1.192 1.002-6.597c.552-2.992-.361-3.75-2.653-5.339c-.723-.498-1.312-.978-1.31-1.066s.725-.818 1.606-1.621l1.602-1.46l.618.5c1.28 1.196 2.267 2.203 3.87 3.167c.113.104 4.426.083 5.746-.623c.672-.672.783-1.353.369-2.261c-.387-.85-1.22-1.166-3.061-1.166h-1.632l-2.025-1.653c-2.924-2.385-3.275-2.611-4.059-2.611c-.734 0-1.352.497-5.02 4.037c-1.295 1.222-2.672 2.487-3.347 4.066c-.177 1.09.56 1.433 2.946 3.053c1.18.8 2.258 1.59 2.394 1.754c.185.223.19.743.018 2.061c-.126.97-.29 2.459-.364 3.309l-.135 1.545l.02.128c.206 1.33 2.57 1.623 3.415.777");
}

</style>
