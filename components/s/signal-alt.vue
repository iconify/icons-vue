<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw0f0ebnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fw0f0ebnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:signal-alt" /></template>
