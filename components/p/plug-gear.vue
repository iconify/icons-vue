<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndvy_ubls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndvy_ubls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:plug-gear" /></template>
