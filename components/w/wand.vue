<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4eos-rnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wand" /></template>
<style>
.v4eos-rnt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.5858 3.2929L20.7071 5.4142C21.0976 5.8047 21.0976 6.4379 20.7071 6.8284L6.8284 20.7071C6.4379 21.0976 5.8047 21.0976 5.4142 20.7071L3.2929 18.5858C2.9024 18.1953 2.9024 17.5621 3.2929 17.1716L17.1716 3.2929C17.5621 2.9024 18.1953 2.9024 18.5858 3.2929ZM13.2908 7.1737L16.8263 10.7092");
}

</style>
