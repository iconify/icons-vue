<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve53p6bmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve53p6bmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:puzzle-fill-round" /></template>
