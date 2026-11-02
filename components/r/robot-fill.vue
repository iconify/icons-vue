<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwod1ybtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwod1ybtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:robot-fill" /></template>
