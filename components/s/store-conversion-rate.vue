<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbgtzlt_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:store-conversion-rate" /></template>
<style>
.kbgtzlt_y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 15.5L15 3M3.25 5.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm11.578 6.59q-.068-.175-.161-.337q-.094-.163-.211-.31t-.254-.274q-.137-.128-.292-.234q-.155-.105-.324-.187q-.169-.081-.348-.137q-.18-.055-.365-.083T12.5 10.5q-.123 0-.245.012t-.243.036q-.12.024-.238.06t-.231.082q-.113.047-.221.105q-.109.058-.211.126q-.102.069-.197.146q-.095.078-.182.165t-.165.182t-.146.197t-.126.211t-.105.221q-.047.114-.082.231t-.06.238q-.024.121-.036.243T10 13t.012.245t.036.243q.024.12.06.238t.082.231q.047.113.105.221q.058.109.126.211q.069.102.146.197q.078.095.165.182t.182.165t.197.146t.211.126t.221.105q.114.047.231.082t.238.06q.121.024.243.036t.245.012q.38 0 .742-.113M16 15.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1.75 6c0-1.75 1.75-3 3.75-3s3.75 1.25 3.75 3");
}

</style>
