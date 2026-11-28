<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otok5pczo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otok5pczo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-braces-solid" /></template>
