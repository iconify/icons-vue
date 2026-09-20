<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g65u_6oub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g65u_6oub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:train-3-fill" /></template>
