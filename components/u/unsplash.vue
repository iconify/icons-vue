<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjsxf6bra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjsxf6bra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:unsplash" /></template>
