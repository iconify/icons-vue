<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyng5hbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nyng5hbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:modsawup" /></template>
