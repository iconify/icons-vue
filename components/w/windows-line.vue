<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mer4-ryno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mer4-ryno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:windows-line" /></template>
