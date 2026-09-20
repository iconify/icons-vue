<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_pdg2bef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_pdg2bef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:qq" /></template>
