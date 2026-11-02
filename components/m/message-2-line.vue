<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpmordbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpmordbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-2-line" /></template>
