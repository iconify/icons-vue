<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8l9ejb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="m8l9ejb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:text-vertical" /></template>
