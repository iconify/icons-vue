<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuzru93kj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuzru93kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:sparkles-solid" /></template>
