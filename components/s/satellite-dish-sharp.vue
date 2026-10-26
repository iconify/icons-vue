<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xitabn1so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:satellite-dish-sharp" /></template>
<style>
.xitabn1so {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.2781 8.7225C2.8194 10.1811 2 12.1594 2 14.2222C2 18.5178 5.4822 22 9.7778 22C11.8406 22 13.8189 21.1806 15.2775 19.7219ZM9.7778 14.2222L12.2929 11.7071M12.1111 6.4444L13.1111 6.4444C15.5657 6.4444 17.5556 8.4343 17.5556 10.8889L17.5556 11.8889M12.1111 2L13.1111 2C18.0203 2 22 5.9797 22 10.8889L22 11.8889");
}

</style>
