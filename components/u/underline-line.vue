<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd5mx2bxw.css';
import '../../css/f/ffx80zbns.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 sd5mx2bxw"/><path class="clr-i-outline clr-i-outline-path-2 ffx80zbns"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:underline-line" /></template>
