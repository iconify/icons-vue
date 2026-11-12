<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="yx7codbhz"/><path class="n3w6d7hoa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:snowflake-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n3w6d7hoa {
  d: path("M3.33925 7.00005L6.80335 9.00005M6.80335 9.00005L11.9994 12M6.80335 9.00005L5.70527 4.90198M6.80335 9.00005L2.70527 10.0981M11.9994 12L17.1957 15.0001M11.9994 12L17.1955 9.00005M11.9994 12L6.80315 15.0001M17.1957 15.0001L20.6598 17.0001M17.1957 15.0001L21.2937 13.902M17.1957 15.0001L18.2937 19.0981M20.6596 7.00005L17.1955 9.00005M17.1955 9.00005L18.2935 4.90198M17.1955 9.00005L21.2935 10.0981M6.80315 15.0001L3.33905 17.0001M6.80315 15.0001L2.70508 13.902M6.80315 15.0001L5.70508 19.0981");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.yx7codbhz {
  d: path("M12 2V6M12 6V18M12 6L15 3M12 6L9 3M12 18V22M12 18L15 21M12 18L9 21");
}

</style>
