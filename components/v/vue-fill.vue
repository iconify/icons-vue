<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sodb7pimc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sodb7pimc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vue-fill" /></template>
