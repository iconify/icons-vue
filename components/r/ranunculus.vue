<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqcn73bhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ranunculus" /></template>
<style>
.kqcn73bhs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.108 15.766q.852-2.082-.379-3.766q1.231-1.684.379-3.766q-.853-2.087-2.92-2.422q-.335-2.067-2.422-2.92q-2.082-.852-3.766.379q-1.684-1.231-3.766-.379q-2.087.853-2.422 2.92q-2.067.335-2.92 2.422q-.852 2.082.379 3.766q-1.231 1.684-.379 3.766q.853 2.087 2.92 2.422q.335 2.067 2.422 2.92q2.082.852 3.766-.379q1.684 1.231 3.766.379q2.087-.853 2.422-2.92q2.067-.335 2.92-2.422m-13.356-1.34Q6.531 13.585 6.531 12t1.221-2.426q.102-1.508 1.506-2.31q1.397-.799 2.742-.131q1.345-.668 2.742.131q1.404.802 1.506 2.31q1.221.841 1.221 2.426t-1.221 2.426q-.102 1.508-1.506 2.31q-1.397.799-2.742.131q-1.345.668-2.742-.131q-1.404-.802-1.506-2.31");
}

</style>
