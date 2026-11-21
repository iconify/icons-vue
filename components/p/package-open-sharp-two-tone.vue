<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="z2zc-obyu"/><path class="xptei9bii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:package-open-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xptei9bii {
  d: path("M12 13.2413L8.1314 16.2413L2 12.7413L5 9.7413L12 6.2413L15.5449 2L22 5.2413L19 9.7413L19 18.618L12 22L5 18.618L5 14.4538M5 9.7413L12 13.2413L19 9.7413M12 13.2413L12 22M12 6.2413L19 9.7413");
}

.z2zc-obyu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 15.0345L1.5043 13.6098C1.1925 13.4318 1 13.1003 1 12.7413C1 12.4761 1.1054 12.2218 1.2929 12.0342L4.2929 9.0342C4.3689 8.9582 4.4567 8.895 4.5528 8.8469L11.3664 5.4401L14.7776 1.3587C14.9676 1.1314 15.2486 1 15.5449 1C15.7007 1 15.8544 1.0364 15.9936 1.1063L22.4487 4.3477C22.7867 4.5174 23 4.8632 23 5.2413C23 5.4387 22.9416 5.6318 22.8321 5.796L20 10.0441L20 18.618C20 19.0017 19.7805 19.3515 19.435 19.5184L12.435 22.9004C12.2994 22.966 12.1507 23 12 23C11.8493 23 11.7006 22.966 11.565 22.9004L4.565 19.5184C4.2195 19.3515 4 19.0017 4 18.618Z");
  stroke: none;
}

</style>
