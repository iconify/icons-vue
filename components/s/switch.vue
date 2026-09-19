<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct6z4mrtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ct6z4mrtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:switch" /></template>
