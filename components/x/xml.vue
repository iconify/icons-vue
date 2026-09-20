<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2171wanj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2171wanj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:xml" /></template>
