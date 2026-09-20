<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlixq-brh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlixq-brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:screenshot-line" /></template>
