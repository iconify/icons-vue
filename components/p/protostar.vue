<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sep5gabqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:protostar" /></template>
<style>
.sep5gabqe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.483 6.843Q13.226 5.644 12 5.644q-1.227 0-1.483 1.199l-.259 1.206q-2.96.171-5.218.943Q1.75 10.118 1.75 12t3.29 3.008q2.258.772 5.218.943l.259 1.206q.256 1.199 1.483 1.199t1.483-1.199l.259-1.206q2.96-.171 5.218-.943q3.29-1.126 3.29-3.008t-3.29-3.008q-2.258-.772-5.218-.943z");
}

</style>
