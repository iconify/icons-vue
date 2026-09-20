<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e09p27jqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e09p27jqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:nextflow" /></template>
