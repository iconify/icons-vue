<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4kw_vbfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4kw_vbfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:meeting" /></template>
