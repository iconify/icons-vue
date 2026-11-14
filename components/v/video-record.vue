<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4bwpsbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:video-record" /></template>
<style>
.u4bwpsbwf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 5.25h6q1.76 0 3.005 1.245q.994.994 1.194 2.317l4.966-2.483q.066-.033.137-.052q.071-.02.145-.025t.147.004t.143.032q.07.024.134.06q.065.037.12.085q.056.049.101.107q.046.059.079.125q.079.158.079.335v10q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.177 0-.335-.079l-4.966-2.483q-.2 1.323-1.194 2.317Q13.76 18.75 12 18.75H6q-1.76 0-3.005-1.245T1.75 14.5v-5q0-1.76 1.245-3.005T6 5.25m10.25 8.286l4.5 2.25V8.214l-4.5 2.25zM6.25 12q0 2.75 2.75 2.75T11.75 12T9 9.25T6.25 12");
}

</style>
