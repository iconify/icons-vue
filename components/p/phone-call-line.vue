<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2h20g36s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2h20g36s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:phone-call-line" /></template>
