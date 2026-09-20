<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n5y7hcert"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:math-symbols-48-filled" /></template>
<style>
.n5y7hcert {
  fill: currentColor;
  d: path("M12.5 4A1.5 1.5 0 0 1 14 5.5V11h5.5a1.5 1.5 0 0 1 0 3H14v5.5a1.5 1.5 0 0 1-3 0V14H5.5a1.5 1.5 0 0 1 0-3H11V5.5A1.5 1.5 0 0 1 12.5 4m15.998 7a1.5 1.5 0 0 0 0 3h14a1.5 1.5 0 1 0 0-3zm-1.496 24.5a1.5 1.5 0 0 1 1.5-1.5h14a1.5 1.5 0 0 1 0 3h-14a1.5 1.5 0 0 1-1.5-1.5M35.5 32a2 2 0 1 0 0-4a2 2 0 0 0 0 4m2 9a2 2 0 1 1-4 0a2 2 0 0 1 4 0M4.19 27.19a1.5 1.5 0 0 1 2.12 0l6.19 6.189l6.19-6.19a1.5 1.5 0 0 1 2.12 2.122L14.622 35.5l6.19 6.19a1.5 1.5 0 0 1-2.122 2.12l-6.19-6.188l-6.19 6.19a1.5 1.5 0 0 1-2.12-2.122l6.189-6.189l-6.19-6.19a1.5 1.5 0 0 1 0-2.12");
}

</style>
