<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6vyzacvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6vyzacvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wavy-duocolor-round" /></template>
