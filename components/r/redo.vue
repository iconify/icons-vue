<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol8rzibii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ol8rzibii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:redo" /></template>
