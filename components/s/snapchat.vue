<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lubrr7x8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lubrr7x8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:snapchat" /></template>
