<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sj2phmb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pin-history-sharp" /></template>
<style>
.sj2phmb6d {
  fill: currentColor;
  d: path("M13.866 12.789L11.5 10.404V6.769h1v3.214l2.073 2.098zM5 10.025h1q0 .939.238 1.795t.737 1.64q.758 1.165 1.735 2.107q.976.943 1.832 2.016q.431.533.79 1.104q.359.57.643 1.186q.292-.615.666-1.177q.375-.561.8-1.113q.855-1.054 1.816-2.003t1.705-2.12q.5-.764.769-1.633T18 10.025q.02-2.5-1.753-4.262Q14.475 4 11.975 4q-1.525 0-2.86.737q-1.336.736-2.142 2.032h1.796v1H5V4h1v2.475q.933-1.614 2.524-2.544Q10.116 3 11.975 3q2.927 0 4.976 2.049T19 10.025q0 1.085-.312 2.094q-.311 1.01-.884 1.889q-.804 1.234-1.835 2.229t-1.946 2.136q-.342.437-.641.883t-.516.952l-.156.35q-.106.211-.312.327q-.206.115-.417.115q-.256 0-.442-.109q-.187-.108-.293-.333l-.155-.35q-.218-.506-.504-.955q-.287-.45-.63-.88q-.895-1.154-1.97-2.13t-1.835-2.235q-.604-.854-.878-1.876T5 10.025");
}

</style>
