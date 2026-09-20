<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9be-4b6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9be-4b6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:things" /></template>
