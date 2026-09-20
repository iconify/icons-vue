<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8xgzym_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8xgzym_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:openzfs" /></template>
