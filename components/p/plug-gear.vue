<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdr48f5mp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdr48f5mp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:plug-gear" /></template>
