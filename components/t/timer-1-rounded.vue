<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7tnpzbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:timer-1-rounded" /></template>
<style>
.b7tnpzbmg {
  fill: currentColor;
  d: path("M12.947 17.936q-.178-.18-.178-.436V7.73q0-.268-.173-.441t-.442-.173H9.616q-.257 0-.436-.18T9 6.497t.18-.435t.436-.178h2.769q.666 0 1.14.474Q14 6.834 14 7.5v10q0 .257-.18.436q-.18.18-.438.18q-.257 0-.435-.18");
}

</style>
