<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2lwzgb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:press-vest" /></template>
<style>
.q2lwzgb7l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 1.75H8.5q-.07 0-.14.013q-.069.013-.135.039q-.065.026-.125.063q-.059.038-.111.086t-.093.105q-.042.057-.073.12q-.03.064-.048.132t-.023.139q-.364 5.09-3.531 6.357q-.104.041-.191.112q-.088.07-.151.164q-.063.093-.096.2t-.033.22V20q0 2.25 2.25 2.25h12q2.25 0 2.25-2.25V9.5q0-.112-.033-.22q-.033-.107-.096-.2t-.151-.164q-.087-.071-.191-.112q-3.167-1.267-3.531-6.357q-.005-.071-.023-.139t-.048-.132t-.073-.12q-.041-.057-.093-.105t-.111-.086q-.06-.037-.125-.063q-.066-.026-.135-.039q-.07-.013-.14-.013H14q-.099 0-.195.026t-.181.075q-.086.05-.156.12q-.07.071-.119.157L12 4.488l-1.349-2.36q-.049-.086-.119-.157q-.07-.07-.156-.12t-.181-.075Q10.099 1.75 10 1.75m-2.75 12.5q0-2.5 2.5-2.5h4.5q2.5 0 2.5 2.5v1q0 2.5-2.5 2.5h-4.5q-2.5 0-2.5-2.5z");
}

</style>
