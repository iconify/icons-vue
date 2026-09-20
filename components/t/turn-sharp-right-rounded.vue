<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo3trcctb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:turn-sharp-right-rounded" /></template>
<style>
.yo3trcctb {
  fill: currentColor;
  d: path("M6.288 20.713Q6 20.425 6 20v-5q0-.825.588-1.412T8 13h8V6.8l-.9.9q-.275.275-.7.275t-.7-.275t-.275-.7t.275-.7l2.6-2.6q.3-.3.7-.3t.7.3l2.6 2.6q.275.275.275.7t-.275.7t-.7.275t-.7-.275l-.9-.9V13q0 .825-.587 1.413T16 15H8v5q0 .425-.288.713T7 21t-.712-.288");
}

</style>
