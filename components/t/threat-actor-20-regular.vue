<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="difyw2rrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:threat-actor-20-regular" /></template>
<style>
.difyw2rrk {
  fill: currentColor;
  d: path("M9.998 2a8 8 0 0 1 7.415 5h.087A1.5 1.5 0 0 1 19 8.5v1c0 .653-.418 1.206-1 1.412V13a4 4 0 0 1-4 4h-.094a4 4 0 0 1-2.828-1.172l-.724-.724a.5.5 0 0 0-.708 0l-.725.724A4 4 0 0 1 6.093 17H6a4 4 0 0 1-4-4v-2.088A1.5 1.5 0 0 1 1 9.5v-1A1.5 1.5 0 0 1 2.5 7h.083a8 8 0 0 1 7.415-5m-5.73 10a2 2 0 1 0 3.464 2zm8 1.999a2 2 0 0 0 3.463-2zM2.5 8a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 .5.5h15a.5.5 0 0 0 .5-.5v-1a.5.5 0 0 0-.5-.5zm7.498-5a7 7 0 0 0-6.325 4h12.65a7 7 0 0 0-6.325-4");
}

</style>
