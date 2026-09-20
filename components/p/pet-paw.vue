<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2i2aodww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="k2i2aodww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:pet-paw" /></template>
