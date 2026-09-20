<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2991i05g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:work-sharp" /></template>
<style>
.e2991i05g {
  fill: currentColor;
  d: path("M2 21V6h6V2h8v4h6v15zm8-15h4V4h-4z");
}

</style>
