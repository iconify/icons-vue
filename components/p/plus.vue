<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4h6tk3ds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="m4h6tk3ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:plus" /></template>
