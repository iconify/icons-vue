<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y20p6kbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y20p6kbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-right-fill-round" /></template>
