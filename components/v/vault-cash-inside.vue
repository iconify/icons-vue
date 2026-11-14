<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2ypp8bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:vault-cash-inside" /></template>
<style>
.s2ypp8bao {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.959 4.459Q2.25 7.169 2.25 11t2.709 6.541q2.71 2.709 6.541 2.709l.137-.001Q11.5 19.693 11.5 19v-2q0-1.394.555-2.233Q11.326 15 10.5 15q-2.071 0-3.536-1.464q-.288-.289-.52-.601q-.206-.092-.327-.282q-.127-.201-.116-.438Q5.5 11.211 5.5 10q0-2.071 1.464-3.536Q8.429 5 10.499 5h.002q2.07 0 3.535 1.464Q15.5 7.929 15.5 10t-1.464 3.536l-.053.051Q14.448 13.5 15 13.5h5.43q.32-1.184.32-2.5q0-3.831-2.709-6.541Q15.331 1.75 11.5 1.75T4.959 4.459M20.5 14.75H15q-2.25 0-2.25 2.25v2q0 2.25 2.25 2.25h5.5q2.25 0 2.25-2.25v-2q0-2.25-2.25-2.25M14.25 17q0-.75.75-.75h2.75q-2 0-2 1.75t2 1.75H15q-.75 0-.75-.75zm3.5 2.75q2 0 2-1.75t-2-1.75h2.75q.75 0 .75.75v2q0 .75-.75.75zm-.401-1.577q.124.077.401.077q.5 0 .5-.25q0-.231-.426-.249q-.233.221-.475.422");
}

</style>
