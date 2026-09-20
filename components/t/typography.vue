<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9eak0b-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="g9eak0b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:typography" /></template>
