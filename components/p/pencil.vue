<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="xs-3avl8y"/><path class="rytph8etf"/><path class="xgcq_320h"/><path class="q3yt1eb0q"/><path class="gn1s3n6cm"/><path class="b7uu55wme"/><path class="v58qtebmq"/><path class="y740jzbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:pencil" /></template>
<style>
.b7uu55wme {
  fill: var(--svg-color--e7e6e6, #e7e6e6);
  d: path("M19.843 7.122L5.128 18.07L4.01 16.569L18.726 5.626zM1.777 13.569L16.496 2.622l1.116 1.5L2.893 15.07z");
}

.gn1s3n6cm {
  fill: var(--svg-color--bcbdbf, #bcbdbf);
  d: path("M2.893 15.07L17.61 4.127l1.116 1.501L4.009 16.571z");
}

.q3yt1eb0q {
  fill: var(--svg-color--ea97bd, #ea97bd);
  d: path("M15.784 1.668c1.32 1.768.81 4.376-1.137 5.824l-7.673 5.706c-1.945 1.452-4.588 1.185-5.906-.583c-1.32-1.772-.809-4.38 1.137-5.824l7.673-5.71c1.945-1.447 4.59-1.185 5.906.587");
}

.rytph8etf {
  fill: var(--svg-color--da4241, #da4241);
  d: path("m1.976 13.841l5.112-3.803L39.41 53.483l-5.112 3.803zm10.611-7.898l4.117-3.06l32.3 43.461l-4.117 3.06z");
}

.v58qtebmq {
  fill: var(--svg-color--f79420, #f79420);
  d: path("m47.4 57.61l-.842.63l-7.148-4.76l5.49-4.08z");
}

.xgcq_320h {
  fill: var(--svg-color--e58732, #e58732);
  d: path("m41.655 51.81l7.355-5.47l.788 8.75l.798 8.738l-8.146-3.278l-8.15-3.27z");
}

.xs-3avl8y {
  fill: var(--svg-color--ee4237, #ee4237);
  d: path("M1.979 13.832L16.698 2.885l32.316 43.45l-14.719 10.947z");
}

.y740jzbwz {
  fill: var(--svg-color--424143, #424143);
  d: path("m42.05 60.39l.4.16l8.15 3.273l-.794-8.743l-.042-.427z");
}

</style>
