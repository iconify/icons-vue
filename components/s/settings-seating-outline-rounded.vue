<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-fqq1bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settings-seating-outline-rounded" /></template>
<style>
.s-fqq1bjv {
  fill: currentColor;
  d: path("M8.308 21q-.31 0-.52-.22t-.211-.52t.21-.511t.52-.21t.521.21t.21.52q0 .29-.21.51t-.52.221m3.673 0q-.31 0-.52-.22t-.211-.52t.21-.511t.52-.21t.521.21t.21.52q0 .29-.21.51t-.52.221m3.673 0q-.29 0-.51-.22t-.221-.52t.22-.511t.52-.21t.511.21t.21.52q0 .29-.21.51t-.52.221m-6.78-3.913q-.143-.144-.143-.356v-2.327H8.35q-.627 0-1.096-.429t-.52-1.05l-.653-8.062q-.031-.348.202-.605t.6-.258h.932q.876 0 1.518.565q.642.566.784 1.435l.594 4.096h4.02q1.361 0 2.315.964q.954.963.954 2.344v.23q0 .31-.23.54t-.54.23h-1.076v2.327q0 .212-.144.356t-.357.144t-.356-.144t-.143-.356v-2.327H9.73v2.327q0 .212-.144.356t-.357.144t-.356-.144M17 13.404q0-.96-.667-1.634q-.666-.674-1.602-.674H9.858l-.716-4.938q-.088-.51-.463-.834T7.815 5H7.08l.656 7.846q.019.25.182.404t.414.154zm-9.266 0");
}

</style>
