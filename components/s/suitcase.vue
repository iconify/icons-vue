<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbxg65bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbxg65bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:suitcase" /></template>
