<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b38tdlapu"/><path class="qrcle2bnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wand-sharp-duotone" /></template>
<style>
.b38tdlapu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.1716 2.2929L21.7071 5.8284C22.0976 6.219 22.0976 6.8521 21.7071 7.2426L7.2426 21.7071C6.8521 22.0976 6.219 22.0976 5.8284 21.7071L2.2929 18.1716C1.9024 17.781 1.9024 17.1479 2.2929 16.7574L16.7574 2.2929C17.1479 1.9024 17.781 1.9024 18.1716 2.2929Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.qrcle2bnq {
  d: path("M12.418 6.6322L17.3678 11.582L7.2426 21.7071C6.8521 22.0976 6.219 22.0976 5.8284 21.7071L2.2929 18.1716C1.9024 17.781 1.9024 17.1479 2.2929 16.7574L12.418 6.6322Z");
}

</style>
