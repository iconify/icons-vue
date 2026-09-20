<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofqds83lo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofqds83lo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:php-cs-fixer" /></template>
