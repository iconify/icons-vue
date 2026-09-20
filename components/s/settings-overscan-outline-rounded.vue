<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqun6ht2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settings-overscan-outline-rounded" /></template>
<style>
.cqun6ht2z {
  fill: currentColor;
  d: path("M6.846 10.87q0-.137-.121-.19t-.227.053l-.975.975q-.13.13-.13.292t.13.292l.975.975q.106.106.227.053t.121-.19zm6.285 4.284h-2.262q-.136 0-.19.121q-.052.121.054.227l.975.975q.13.13.292.13t.292-.13l.975-.975q.106-.106.053-.227t-.19-.121m0-6.308q.137 0 .19-.121t-.053-.227l-.975-.975q-.13-.13-.292-.13t-.292.13l-.975.975q-.106.106-.053.227t.19.121zm4.024 2.023v2.262q0 .136.121.19q.121.052.227-.054l.975-.975q.13-.13.13-.292t-.13-.292l-.975-.975q-.106-.106-.227-.053t-.121.19M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zm0-1h14.769q.23 0 .423-.192t.192-.424V6.616q0-.231-.192-.424T19.385 6H4.615q-.23 0-.423.192T4 6.616v10.769q0 .23.192.423t.423.192M4 18V6z");
}

</style>
