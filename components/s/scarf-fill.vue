<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oue1irbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oue1irbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:scarf-fill" /></template>
