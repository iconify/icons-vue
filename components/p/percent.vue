<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kumx2fb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kumx2fb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:percent" /></template>
