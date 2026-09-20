<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpqcr1ehv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpqcr1ehv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shower-fill" /></template>
