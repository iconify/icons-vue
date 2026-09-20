<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3t_iyber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h3t_iyber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:paper-and-pencil" /></template>
