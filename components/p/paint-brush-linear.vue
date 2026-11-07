<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eye35dkqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eye35dkqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paint-brush-linear" /></template>
