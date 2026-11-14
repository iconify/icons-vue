<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0x__bbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:new-in-sign" /></template>
<style>
.e0x__bbrf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7.5v-1a2 2 0 1 0-2-2m4.548 9h-6.43q-.131 0-.261-.021q-.129-.021-.254-.063q-.124-.042-.24-.103t-.221-.14T6.946 13q-.091-.095-.165-.203t-.131-.226t-.092-.245q-.037-.126-.053-.256q-.015-.131-.01-.262t.031-.259q.027-.129.073-.252q.047-.122.112-.236q.066-.114.149-.215q.083-.102.181-.189t.209-.157l3.348-2.115q.157-.099.325-.175q.169-.076.347-.127t.361-.078t.369-.026t.369.026t.361.078q.178.051.347.127t.325.175L16.75 10.5q.165.105.301.246q.136.14.235.31t.154.356q.055.188.065.384m.525 3.174l.295.677a1.5 1.5 0 0 0 .778.778l.677.295a.578.578 0 0 1 0 1.06l-.677.295a1.5 1.5 0 0 0-.778.778l-.295.677a.578.578 0 0 1-1.06 0l-.295-.677a1.5 1.5 0 0 0-.778-.778l-.677-.295a.578.578 0 0 1 0-1.06l.677-.295a1.5 1.5 0 0 0 .778-.778l.295-.677a.578.578 0 0 1 1.06 0");
}

</style>
