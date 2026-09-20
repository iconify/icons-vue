<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqpax39ar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqpax39ar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:spell-check-2" /></template>
