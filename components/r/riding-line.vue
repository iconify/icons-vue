<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki8ssi60z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ki8ssi60z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:riding-line" /></template>
