<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c270pqb-c.css';
import '../../css/f/fu3bak12h.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="c270pqb-c clr-i-outline clr-i-outline-path-1"/><path class="clr-i-outline clr-i-outline-path-2 fu3bak12h"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:vm-line" /></template>
