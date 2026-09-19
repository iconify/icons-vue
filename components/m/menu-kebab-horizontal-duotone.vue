<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rla7-lvwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rla7-lvwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:menu-kebab-horizontal-duotone" /></template>
