<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjc0ajicx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjc0ajicx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:treemap-solid" /></template>
