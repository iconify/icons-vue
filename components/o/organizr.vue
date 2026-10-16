<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyc_-lbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":600,"height":600};
const content = `<path class="lyc_-lbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:organizr" /></template>
