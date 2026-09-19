<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aq-x_vb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="aq-x_vb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:researchgate" /></template>
