<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdanj7bcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdanj7bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:umbrella-2-line" /></template>
