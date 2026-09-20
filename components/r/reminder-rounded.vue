<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qf92k2jgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:reminder-rounded" /></template>
<style>
.qf92k2jgl {
  fill: currentColor;
  d: path("M6.692 9h1.5V7.5q0-.617-.441-1.059Q7.309 6 6.692 6t-1.058.441T5.192 7.5t.442 1.059T6.692 9m4.116 0q.617 0 1.058-.441q.442-.442.442-1.059t-.442-1.059Q11.425 6 10.808 6t-1.059.441T9.308 7.5V9zm-1.61 2.539h7.379q1.02 0 1.721.702q.702.701.702 1.72V17.5q0 1.458-1.03 2.479T15.48 21h-4.313q-.815 0-1.552-.338t-1.22-.985l-4.506-5.952q-.104-.148-.098-.316t.128-.292q.25-.275.595-.336t.655.121l3.023 1.49V10h-1.5q-1.038 0-1.769-.73t-.73-1.77t.73-1.77T6.693 5q.428 0 .81.146t.69.414V3.5q0-.213.143-.357T8.692 3t.36.143q.146.144.146.357v2.112q.33-.297.742-.454q.41-.158.868-.158q1.038 0 1.769.73t.73 1.77t-.73 1.77t-1.77.73H9.199z");
}

</style>
