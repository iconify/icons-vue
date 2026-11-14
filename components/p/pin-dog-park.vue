<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fctv2m1di"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-dog-park" /></template>
<style>
.fctv2m1di {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.935 3.638q-1.23 2.423.465 4.152L7.79 12.4q-1.729-1.695-4.152-.465q-2.833 1.437-1.881 4.467q.807 2.573 3.196 2.645q.072 2.389 2.645 3.196q3.03.952 4.467-1.881q1.23-2.423-.465-4.152l4.61-4.61q1.729 1.695 4.152.465q2.833-1.437 1.881-4.467q-.807-2.573-3.196-2.645q-.072-2.389-2.645-3.196q-3.03-.952-4.467 1.881");
}

</style>
