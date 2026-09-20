<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba-ur9lbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba-ur9lbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:run-treadmill-line" /></template>
