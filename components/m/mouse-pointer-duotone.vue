<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0xvr4gta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary z0xvr4gta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mouse-pointer-duotone" /></template>
