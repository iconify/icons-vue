<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mei2r4bmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mei2r4bmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:palette-plus" /></template>
