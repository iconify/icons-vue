<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djdzd-6ny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djdzd-6ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:t-shirt-fill" /></template>
