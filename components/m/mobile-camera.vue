<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocyzodxns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-camera" /></template>
<style>
.ocyzodxns {
  fill: currentColor;
  d: path("M7.616 22q-.667 0-1.141-.475T6 20.386V3.615q0-.69.463-1.152T7.616 2h8.846q.666 0 1.14.475t.475 1.14v2.577h-2.748l-.885.866q-1.486.077-2.504 1.116q-1.017 1.04-1.017 2.557v3.404q0 1.521 1.076 2.597t2.597 1.076h3.481v2.576q0 .667-.475 1.141t-1.14.475zm4.972-15.914q.22-.222.22-.549t-.222-.547t-.549-.22t-.548.22t-.22.55t.222.547t.549.22t.548-.22m2.012 9.336q-.533 0-.912-.376t-.38-.913v-3.4q0-.532.375-.912q.376-.38.913-.38h.856l.856-.865h1.7l.85.865h.851q.531 0 .911.376t.38.913v3.401q0 .532-.376.911t-.912.38zm3.609-1.945q.445-.445.445-1.058q0-.612-.445-1.045t-1.055-.433t-1.055.433t-.445 1.045t.445 1.058t1.055.445t1.055-.445");
}

</style>
