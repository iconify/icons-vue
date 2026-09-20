<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p44r91bug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:quiz-48-filled" /></template>
<style>
.p44r91bug {
  fill: currentColor;
  d: path("M35.75 6A6.25 6.25 0 0 1 42 12.25v23.5A6.25 6.25 0 0 1 35.75 42h-23.5A6.25 6.25 0 0 1 6 35.75v-23.5A6.25 6.25 0 0 1 12.25 6zm-23.5 28a1.25 1.25 0 1 0 0 2.5l24.5.001a1.25 1.25 0 0 0 0-2.5zm0-6.005a1.25 1.25 0 0 0 0 2.5l24.5.001a1.25 1.25 0 0 0 0-2.5zm7.248-16.997a1.25 1.25 0 0 0-1.155.774l-4.748 11.505a1.25 1.25 0 0 0 2.31.954l.707-1.713h5.775l.708 1.713a1.25 1.25 0 0 0 2.31-.954l-4.752-11.506a1.25 1.25 0 0 0-1.155-.773m12.25 0c-.69 0-1.25.56-1.25 1.25V15H27.75a1.25 1.25 0 1 0 0 2.5h2.748v2.748a1.25 1.25 0 0 0 2.5 0V17.5h2.752a1.25 1.25 0 0 0 0-2.5h-2.752v-2.752c0-.69-.56-1.25-1.25-1.25m-10.393 9.02h-3.711l1.854-4.494z");
}

</style>
