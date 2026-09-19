<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_2i5mwhi.css';
import '../../css/p/pm4-heb4o.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 j_2i5mwhi"/><path class="clr-i-solid clr-i-solid-path-2 pm4-heb4o"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:resource-pool-solid" /></template>
