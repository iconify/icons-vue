<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuwi-34aa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuwi-34aa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:plug-zap-filled" /></template>
