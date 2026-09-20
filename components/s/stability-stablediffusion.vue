<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai6km_1tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ai6km_1tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:stability-stablediffusion" /></template>
