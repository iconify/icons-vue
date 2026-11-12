<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ecxmxhl9m"/><path class="uhv43pf8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:plain-3-bold-duotone" /></template>
<style>
.ecxmxhl9m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m20.352 10.52l-1.716 5.15c-1.21 3.63-1.816 5.446-2.703 5.962c-.844.49-1.887.49-2.73 0c-.888-.516-1.493-2.331-2.703-5.962c-.195-.583-.292-.874-.455-1.118a2.2 2.2 0 0 0-.597-.597c-.244-.163-.535-.26-1.118-.454c-3.63-1.21-5.446-1.816-5.962-2.703a2.72 2.72 0 0 1 0-2.731C2.884 7.18 4.7 6.575 8.33 5.364l5.15-1.716c4.498-1.5 6.747-2.25 7.934-1.062s.438 3.436-1.062 7.935");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.uhv43pf8i {
  fill: currentColor;
  d: path("M13.046 10.902a.75.75 0 0 1 .006-1.06l4.21-4.164a.75.75 0 0 1 1.055 1.066l-4.21 4.164a.75.75 0 0 1-1.061-.006");
}

</style>
