<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_8rf2bon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_8rf2bon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vodafone" /></template>
