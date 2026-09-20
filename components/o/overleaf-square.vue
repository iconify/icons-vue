<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzjeupbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="dzjeupbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:overleaf-square" /></template>
