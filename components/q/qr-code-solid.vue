<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv3b14b5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cv3b14b5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:qr-code-solid" /></template>
