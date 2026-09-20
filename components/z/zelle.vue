<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1nko06zj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1nko06zj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:zelle" /></template>
