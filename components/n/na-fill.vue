<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-v6je9ej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d-v6je9ej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:na-fill" /></template>
