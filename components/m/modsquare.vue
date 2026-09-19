<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl-e23r9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vl-e23r9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:modsquare" /></template>
