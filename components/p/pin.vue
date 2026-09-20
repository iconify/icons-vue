<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg75l3p3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="yg75l3p3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:pin" /></template>
