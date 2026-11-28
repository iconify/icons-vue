<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuraqd2at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuraqd2at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:spoon" /></template>
