<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n1mjunbsu"><path class="l8fstde0p"/><path class="uguzrsb1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:prism" /></template>
<style>
.l8fstde0p {
  d: path("M15.974 19.877s.169.226-3.174-5.627l2.724-4.654l.867 1.626l-1.745 3.045l3.241 5.61zM13.74 6.602l.934 1.643l-3.658 6.005H5.917c.321-.563.659-1.149.957-1.689h3.067zm-1.947 8.773l2.622 4.502h-1.89l-1.7-2.813H4.263l.979-1.689z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.uguzrsb1j {
  d: path("M3.498 19.878a.505.505 0 0 1-.44-.743l.552-.945h6.46l.924 1.677c-.732.01-1.295.01-1.891.01zm17.462-.861s.248.86-.495.86h-.985l-3.27-5.554l.98-1.71zM11.556 4.368a.5.5 0 0 1 .856-.011l.613 1.024l-3.917 6.056H7.234z");
}

</style>
