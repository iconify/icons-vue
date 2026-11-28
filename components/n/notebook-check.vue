<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qoqkcl5ra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qoqkcl5ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:notebook-check" /></template>
