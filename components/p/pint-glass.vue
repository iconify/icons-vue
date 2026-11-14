<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpxej0qxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pint-glass" /></template>
<style>
.lpxej0qxm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 2.25h11q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .037-.004.075l-.229 2.293q.742 1.669-.034 3.338l-1.237 12.369q-.007.068-.026.135q-.019.066-.05.128t-.074.117q-.041.055-.093.101q-.051.046-.11.083q-.059.036-.123.061q-.065.025-.133.037q-.068.013-.137.013H8q-.069 0-.137-.013T7.73 21.7q-.064-.025-.123-.061q-.059-.037-.11-.083t-.093-.101t-.074-.117q-.031-.062-.05-.128q-.019-.067-.026-.135L6.017 8.706q-.776-1.669-.034-3.338l-.229-2.293q-.015-.149.028-.292q.043-.142.138-.258q.094-.115.225-.186q.132-.07.28-.085q.038-.004.075-.004");
}

</style>
