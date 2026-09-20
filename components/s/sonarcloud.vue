<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8hsn8bza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8hsn8bza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:sonarcloud" /></template>
