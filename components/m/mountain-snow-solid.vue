<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_-u3dbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_-u3dbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:mountain-snow-solid" /></template>
