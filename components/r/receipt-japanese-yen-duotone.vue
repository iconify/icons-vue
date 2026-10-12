<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/ernxwjbbg.css';
import '../../css/g/g48c9l9px.css';
import '../../css/a/awesmtr4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ernxwjbbg"/><path class="g48c9l9px"/><path class="awesmtr4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:receipt-japanese-yen-duotone" /></template>
