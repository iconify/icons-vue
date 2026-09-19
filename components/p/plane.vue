<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqc0s_98y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="iqc0s_98y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:plane" /></template>
