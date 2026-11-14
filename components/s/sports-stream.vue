<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk3rz5bkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sports-stream" /></template>
<style>
.dk3rz5bkv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 5.439L8.53 1.97q-.105-.106-.243-.163T8 1.75t-.287.057t-.243.163t-.163.243t-.057.287t.057.287t.163.243l2.719 2.72H6.875q-2.123 0-3.624 1.501T1.75 10.875v4.75q0 2.123 1.501 3.624t3.624 1.501h10.25q2.123 0 3.624-1.501t1.501-3.624v-4.75q0-2.123-1.501-3.624T17.125 5.75h-3.314l2.719-2.72q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043T16 1.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094zm.645 5.252l1.052.622q1.104.654 1.104 1.937t-1.104 1.937l-1.052.622q-1.126.664-2.261.017q-1.134-.648-1.134-1.955v-1.242q0-1.307 1.134-1.955q1.135-.647 2.261.017");
}

</style>
