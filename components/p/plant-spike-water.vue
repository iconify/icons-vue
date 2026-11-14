<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkoozcbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:plant-spike-water" /></template>
<style>
.mkoozcbxk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.048 2.25H6.952q-1.287 0-2.035 1.048t-.329 2.265L5 6.762V6.75q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T5.75 6h8.5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v.012l.412-1.199q.419-1.217-.329-2.265T13.048 2.25m1.801 4.951q-.052.07-.119.126t-.145.094t-.163.059q-.085.02-.172.02h-8.5q-.087 0-.172-.02t-.163-.059t-.145-.094q-.067-.056-.119-.126l2.485 7.229q.58 1.687 2.364 1.687t2.364-1.687zm4.202 5.79q3.199 3.466 3.199 5.509q0 3.75-3.75 3.75t-3.75-3.75q0-2.043 3.199-5.509q.101-.109.237-.172t.284-.068q.149-.006.289.045q.14.052.25.153q.022.02.042.042M16.25 18.5q0-1.306 2.25-3.879q2.25 2.573 2.25 3.879q0 2.25-2.25 2.25t-2.25-2.25");
}

</style>
