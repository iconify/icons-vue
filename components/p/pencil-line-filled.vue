<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrt_dqbuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrt_dqbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:pencil-line-filled" /></template>
