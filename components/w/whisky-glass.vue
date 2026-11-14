<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyw0mlbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:whisky-glass" /></template>
<style>
.lyw0mlbts {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.744 3.907l.668 5.343h13.176l.668-5.343q.018-.148.092-.278q.074-.129.192-.221q.117-.092.261-.131t.292-.021q.073.009.143.032q.071.024.135.06q.064.037.12.085t.101.107q.045.058.078.124q.034.066.053.137q.02.071.025.145t-.004.147L19.22 16.289q.03.103.03.211q0 .205-.104.382l-.152 1.211Q18.662 20.75 16 20.75H8q-2.662 0-2.994-2.657l-.152-1.211q-.104-.177-.104-.382q0-.108.03-.211l-.774-6.196l-.75-6q-.009-.073-.004-.147t.025-.145t.053-.137t.078-.124t.101-.107t.12-.085t.135-.06t.143-.032t.147-.004t.145.025q.071.019.137.053q.066.033.124.078q.059.045.107.101t.085.12q.036.064.06.135q.023.07.032.143M6.412 17.25l.082.657Q6.662 19.25 8 19.25h8q1.338 0 1.506-1.343l.082-.657zm11.363-1.5l.625-5H5.6l.625 5z");
}

</style>
