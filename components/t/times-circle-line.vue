<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9ihphl4d.css';
import '../../css/b/bp242uqss.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 r9ihphl4d"/><path class="bp242uqss clr-i-outline clr-i-outline-path-2"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:times-circle-line" /></template>
