<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q73z4pb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q73z4pb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:pricetag" /></template>
