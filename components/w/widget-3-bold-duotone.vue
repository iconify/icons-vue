<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="rrf3ilijn"/><path class="oe-xab43p"/><g class="mc2zb0bvp"><path class="ajqcms6oz"/><path class="tsfsykbbs"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:widget-3-bold-duotone" /></template>
<style>
.ajqcms6oz {
  d: path("M1.75 6.5C1.75 3.87665 3.87665 1.75 6.5 1.75C9.12335 1.75 11.25 3.87665 11.25 6.5C11.25 9.12335 9.12335 11.25 6.5 11.25C3.87665 11.25 1.75 9.12335 1.75 6.5Z");
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

.oe-xab43p {
  d: path("M11.25 17.5C11.25 14.8766 9.12335 12.75 6.5 12.75C3.87665 12.75 1.75 14.8766 1.75 17.5C1.75 20.1234 3.87665 22.25 6.5 22.25C9.12335 22.25 11.25 20.1234 11.25 17.5Z");
}

.rrf3ilijn {
  d: path("M22.25 6.5C22.25 3.87665 20.1234 1.75 17.5 1.75C14.8766 1.75 12.75 3.87665 12.75 6.5C12.75 9.12335 14.8766 11.25 17.5 11.25C20.1234 11.25 22.25 9.12335 22.25 6.5Z");
}

.tsfsykbbs {
  d: path("M12.75 17.5C12.75 14.8766 14.8766 12.75 17.5 12.75C20.1234 12.75 22.25 14.8766 22.25 17.5C22.25 20.1234 20.1234 22.25 17.5 22.25C14.8766 22.25 12.75 20.1234 12.75 17.5Z");
}

</style>
