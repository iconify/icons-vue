<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvmb1gbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:phone-missed-rounded" /></template>
<style>
.wvmb1gbjz {
  fill: currentColor;
  d: path("m3.342 19.15l-1.511-1.461q-.32-.3-.31-.73q.01-.428.329-.747q1.95-1.99 4.662-3.101T12 12t5.486 1.11q2.708 1.111 4.664 3.102q.32.319.329.748t-.31.729l-1.511 1.461q-.333.314-.724.358q-.392.044-.73-.2l-2.131-1.623q-.296-.227-.434-.485t-.139-.584v-2.793q-1.22-.434-2.277-.629Q13.166 13 12 13t-2.223.194t-2.277.629v2.793q0 .326-.139.584t-.434.485l-2.13 1.623q-.34.244-.73.2q-.392-.044-.725-.358m2.82-10.293Q6.02 8.714 6.02 8.5V4.808q0-.348.23-.578T6.827 4h3.692q.214 0 .357.143t.143.357t-.143.357t-.357.143H7.727l3.833 3.833q.173.173.442.173t.442-.173l4.527-4.527q.146-.146.347-.156t.367.156t.165.357t-.165.356l-4.54 4.54q-.46.46-1.137.46t-1.137-.46L7.02 5.709V8.5q0 .214-.143.357T6.519 9t-.357-.143");
}

</style>
