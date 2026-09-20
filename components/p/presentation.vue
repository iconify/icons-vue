<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyt08dpgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyt08dpgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:presentation" /></template>
