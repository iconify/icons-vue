<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhp-uccox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:profile-frame" /></template>
<style>
.yhp-uccox {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12M12 5.25q-4 0-4 4t4 4t4-4q0-1.657-1.172-2.828Q13.657 5.25 12 5.25m0 9.25q-4.301 0-6.433 4.69q-.03.067-.047.139t-.02.146q-.002.073.01.146t.038.142t.065.132t.089.117t.11.097t.128.074q.135.062.285.067t.288-.048q.14-.052.249-.154t.171-.238Q8.665 16 12 16t5.067 3.81q.031.068.074.128t.097.11t.117.089t.132.065t.142.038t.146.01q.074-.003.146-.02t.139-.047q.068-.031.128-.074t.11-.097t.089-.117t.065-.132t.038-.142t.01-.146q-.003-.074-.02-.146t-.047-.139Q16.301 14.5 12 14.5");
}

</style>
