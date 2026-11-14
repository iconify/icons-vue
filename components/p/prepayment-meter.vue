<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsgxvzu1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:prepayment-meter" /></template>
<style>
.xsgxvzu1p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.125 1.75h-4.25q-2.123 0-3.624 1.501T1.75 6.875v10.25q0 2.123 1.501 3.624t3.624 1.501h4.25q2.123 0 3.624-1.501q.122-.122.235-.249h-.734q-1.553 0-2.652-1.098Q10.5 18.303 10.5 16.75v-3q0-3.75 3.75-3.75h2V6.875q0-2.123-1.501-3.624T11.125 1.75M7.25 4.25h3.5q1.036 0 1.768.732t.732 1.768v.5q0 1.036-.732 1.768t-1.768.732h-3.5q-2.5 0-2.5-2.5v-.5q0-2.5 2.5-2.5m12.5 7h-5.5q-2.5 0-2.5 2.5v3q0 1.036.732 1.768t1.768.732h5.5q1.036 0 1.768-.732t.732-1.768v-3q0-1.036-.732-1.768t-1.768-.732M13.25 14v-.25q0-1 1-1h5.5q1 0 1 1V14zm0 2.75V15.5h7.5v1.25q0 .414-.293.707t-.707.293h-5.5q-.414 0-.707-.293t-.293-.707");
}

</style>
