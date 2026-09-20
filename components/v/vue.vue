<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njca8dbxl.css';
import '../../css/a/as0inn2-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njca8dbxl"/><path class="as0inn2-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:vue" /></template>
