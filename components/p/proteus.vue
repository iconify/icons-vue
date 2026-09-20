<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vba71sb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vba71sb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:proteus" /></template>
