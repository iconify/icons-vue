<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e66-8lbpc.css';
import '../../css/l/l5rcylbor.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 e66-8lbpc"/><path class="clr-i-outline clr-i-outline-path-2 l5rcylbor"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:world-line" /></template>
