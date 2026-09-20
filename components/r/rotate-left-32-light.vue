<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u92fcqbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rotate-left-32-light" /></template>
<style>
.u92fcqbud {
  fill: currentColor;
  d: path("M12.854 2.854a.5.5 0 0 0-.708-.708l-5 5a.5.5 0 0 0 0 .708l5 5a.5.5 0 0 0 .708-.708L8.707 8H23a5 5 0 0 1 0 10h-2.5a.5.5 0 0 0 0 1H23a6 6 0 0 0 0-12H8.707zm-9.11 11.21A.5.5 0 0 0 3 14.5V28a1 1 0 0 0 1 1h24.5a.5.5 0 0 0 .244-.936zM4 28V15.353L26.584 28z");
}

</style>
