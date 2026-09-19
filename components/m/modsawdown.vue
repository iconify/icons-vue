<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xupllvb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xupllvb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:modsawdown" /></template>
