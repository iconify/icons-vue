<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdm0-fbdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdm0-fbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:number-8" /></template>
