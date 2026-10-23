<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5o7yvrrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5o7yvrrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:wine-off" /></template>
