<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etig-_o3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etig-_o3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:paperspace" /></template>
