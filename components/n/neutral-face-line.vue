<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkntmybbm.css';
import '../../css/l/l5rcylbor.css';
import '../../css/u/uzhgw6bwi.css';
import '../../css/u/uot482hxp.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 jkntmybbm"/><path class="clr-i-outline clr-i-outline-path-2 l5rcylbor"/><circle class="clr-i-outline clr-i-outline-path-3 uzhgw6bwi"/><circle class="clr-i-outline clr-i-outline-path-4 uot482hxp"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:neutral-face-line" /></template>
