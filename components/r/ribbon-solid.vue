<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoxxp1nog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eoxxp1nog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ribbon-solid" /></template>
