<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcvhfebrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-camera-outline" /></template>
<style>
.hcvhfebrs {
  fill: currentColor;
  d: path("M7 17.808V21V3zm5.588-11.72q.22-.22.22-.55q0-.329-.22-.549t-.55-.22t-.548.22t-.22.55t.22.549t.549.22t.549-.22m4.489 11.72h1v2.576q0 .672-.472 1.144T16.462 22H7.616q-.672 0-1.144-.472T6 20.385V3.615q0-.69.463-1.152T7.616 2h8.846q.67 0 1.143.472q.472.472.472 1.144v2.576h-1V3.616q0-.27-.173-.443T16.462 3H7.616q-.27 0-.443.173T7 3.616v16.769q0 .269.173.442t.443.173h8.846q.269 0 .442-.173t.173-.442zm-2.48-2.385q-.53 0-.91-.38t-.38-.909v-3.403q0-.529.38-.909t.91-.38h.845l.866-.865H18l.865.865h.847q.529 0 .908.38q.38.38.38.909v3.404q0 .529-.38.908t-.909.38zm3.612-1.945q.445-.445.445-1.055t-.445-1.045t-1.055-.436t-1.055.436q-.445.435-.445 1.045t.445 1.055t1.055.445t1.055-.445");
}

</style>
