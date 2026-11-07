<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iua2v6-9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:party-popper-fill-round" /></template>
<style>
.iua2v6-9n {
  fill: currentColor;
  d: path("M12 5a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm3.01-3a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2Zm.283 5.293l2-2a.999.999 0 1 1 1.414 1.414l-2 2a.999.999 0 1 1-1.414-1.414M5.682 9.791c.021-.931.56-1.735 1.47-2.01c.895-.27 1.867.048 2.67.45c.611.305 1.181.686 1.723 1.1a17 17 0 0 1 1.662 1.462c1.302 1.302 3.618 4.048 3.012 6.055c-.096.325-.272.62-.512.859c-.398.398-.941.598-1.498.611l-7.893 2.631a2.582 2.582 0 0 1-3.265-3.265ZM20.99 10a1 1 0 0 1 0-2H21a1 1 0 0 1 0 2Zm-13.288.057c.053.305.18.596.317.871c.249.497.563.961.9 1.402q.596.774 1.288 1.463q.689.692 1.463 1.288a9 9 0 0 0 1.402.9c.275.137.566.264.871.317l.375-.125c.012-.359-.181-.788-.337-1.101a9 9 0 0 0-.9-1.402a15 15 0 0 0-1.288-1.463a15 15 0 0 0-1.463-1.288a9 9 0 0 0-1.402-.9c-.313-.156-.741-.349-1.101-.337ZM21 12a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2Z");
}

</style>
