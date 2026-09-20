<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="xccqlbalf"/><path class="yyiz0ybcr"/><path class="fa6s8pbfh"/><path class="uf6zdqc3i"/><path class="o45jry72x"/><path class="poscebxge"/><path class="rykj4i97n"/><path class="gobe0bb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:woman-with-headscarf-dark-skin-tone" /></template>
<style>
.fa6s8pbfh {
  fill: var(--svg-color--9266cc, #9266cc);
  d: path("M27.807 16.761C27.807 8.267 21.926 5 18.006 5s-9.8 3.294-9.8 11.761c0 8.494 7.187 11.761 11.107 11.761C22.252 28.521 23.065 30 25 30c5.281 0 2.807-4.419 2.807-13.239");
}

.gobe0bb6t {
  fill: var(--svg-color--553788, #553788);
  d: path("M10 17s3-5 8-5s8 5 8 5s-1-8-8-8s-8 8-8 8");
}

.o45jry72x {
  fill: var(--svg-color--df1f32, #df1f32);
  d: path("M17.944 23.543c-1.605 0-2.446-.794-2.536-.885a.684.684 0 0 1 .96-.974c.035.032.553.491 1.576.491c1.039 0 1.557-.473 1.577-.492a.69.69 0 0 1 .963.02c.26.269.26.691-.004.955c-.089.091-.929.885-2.536.885");
}

.poscebxge {
  d: path("M14.608 17.886a.85.85 0 0 1-.846-.846v-.845c0-.465.381-.846.846-.846s.847.381.847.846v.845a.85.85 0 0 1-.847.846m6.765 0a.85.85 0 0 1-.846-.846v-.845c0-.465.381-.846.846-.846s.846.381.846.846v.845a.85.85 0 0 1-.846.846");
}

.rykj4i97n {
  fill: var(--svg-color--3d2e24, #3d2e24);
  d: path("M18.837 20.5h-1.691a.424.424 0 0 1-.423-.423v-.153c0-.233.189-.424.423-.424h1.691c.232 0 .423.19.423.424v.153a.424.424 0 0 1-.423.423");
}

.uf6zdqc3i {
  fill: var(--svg-color--7c533e, #7c533e);
  d: path("M16.904 11.166c-2.167.265-6.558 3.877-6.719 5.799c.2 5.341 3.62 9.596 7.821 9.596c4.178 0 7.583-4.208 7.818-9.507c-.23-2.372-6.919-6.133-8.92-5.888");
}

.xccqlbalf {
  fill: var(--svg-color--9266cc, #9266cc);
  d: path("M31 36v-3.5c0-3.314-3.685-5.5-7-5.5H12c-3.313 0-7 2.186-7 5.5V36z");
}

.yyiz0ybcr {
  fill: var(--svg-color--744eaa, #744eaa);
  d: path("M27.235 16.761c0-8.494-5.309-11.026-9.229-11.026s-9.8 2.559-9.8 11.026c0 3.489 1.255 6.182.644 8.238C7.65 29.037 11.778 32.506 15 34c4.94 2.29 10-3 10-3c3.975 0 2.235-4.248 2.235-14.239");
}

</style>
