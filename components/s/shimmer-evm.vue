<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_l33p6ko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:shimmer-evm" /></template>
<style>
.a_l33p6ko {
  fill: var(--svg-color--00e0ca, #00e0ca);
  d: path("M18.486 5.427c-2.97-3.175-7.852-3.244-10.904-.153s-3.117 8.171-.146 11.347l1.952-1.978c-1.915-2.06-1.87-5.347.106-7.348a4.864 4.864 0 0 1 7.062.088zM5.514 18.573c2.97 3.175 7.852 3.244 10.904.153s3.117-8.171.146-11.347l-1.952 1.978c1.915 2.06 1.87 5.347-.106 7.348s-5.134 1.96-7.062-.088z");
}

</style>
