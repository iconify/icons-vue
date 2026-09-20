<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/defzuhtie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="defzuhtie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:sensors-off" /></template>
