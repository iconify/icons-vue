<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md_1n2bqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="md_1n2bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:yaml" /></template>
