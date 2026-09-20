<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydkrs6gpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydkrs6gpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:merck" /></template>
