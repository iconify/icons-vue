<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1vww1bqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1vww1bqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:settings-6-fill" /></template>
