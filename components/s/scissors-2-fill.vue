<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzq-0irrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzq-0irrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:scissors-2-fill" /></template>
