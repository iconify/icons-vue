<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydkyh5cpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydkyh5cpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:parachute-line" /></template>
