<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkr6io21r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkr6io21r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:toml" /></template>
