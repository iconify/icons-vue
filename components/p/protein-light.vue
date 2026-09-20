<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjdzg81ar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjdzg81ar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:protein-light" /></template>
