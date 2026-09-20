<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd75_bccp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vd75_bccp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:umbraco" /></template>
