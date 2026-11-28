<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqx47qfla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqx47qfla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:orbit" /></template>
