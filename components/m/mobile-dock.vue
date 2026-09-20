<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tchlk1btk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-dock" /></template>
<style>
.tchlk1btk {
  fill: currentColor;
  d: path("M12.713 5.713Q13 5.425 13 5t-.288-.712T12 4t-.712.288T11 5t.288.713T12 6t.713-.288M18 3v2.05q.425.075.713.413t.287.762v1.55q0 .425-.288.763T18 8.95V17q0 .825-.587 1.413T16 19H8q-.825 0-1.412-.587T6 17V3q0-.825.588-1.412T8 1h8q.825 0 1.413.588T18 3M8 23v-2h8v2z");
}

</style>
