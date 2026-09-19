<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg7qhdhnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lg7qhdhnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:nav-arrow-right-solid" /></template>
