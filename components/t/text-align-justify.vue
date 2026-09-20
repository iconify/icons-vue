<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z58bjmbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z58bjmbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:text-align-justify" /></template>
