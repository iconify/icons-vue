<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8s526brq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8s526brq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:messenger-line" /></template>
