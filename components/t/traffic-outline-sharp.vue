<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb01tgb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:traffic-outline-sharp" /></template>
<style>
.rb01tgb0u {
  fill: currentColor;
  d: path("M12.739 17.3q.319-.314.319-.796q0-.481-.315-.8t-.796-.32t-.8.315q-.32.315-.32.796t.315.801t.796.32t.8-.315m0-4.5q.32-.315.32-.796t-.315-.801t-.796-.32t-.8.315t-.32.796t.315.801t.796.32t.8-.315m0-4.5q.32-.315.32-.796t-.315-.801t-.796-.32t-.8.315t-.32.797t.315.8t.796.32t.8-.315M7.943 20v-2.496q-.967-.235-1.445-.871q-.478-.637-.478-1.402h1.923v-2.342q-.967-.235-1.445-.872q-.478-.636-.478-1.401h1.923V8.273q-.967-.235-1.445-.871Q6.019 6.765 6.019 6h1.923V4h8v2h2.039q0 .765-.536 1.402q-.535.636-1.503.871v2.343h2.039q0 .765-.536 1.401q-.535.637-1.503.872v2.342h2.039q0 .765-.536 1.402q-.535.636-1.503.87V20zm1-1h6V5h-6zm0 0V5z");
}

</style>
