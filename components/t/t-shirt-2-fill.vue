<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmd6mmf_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmd6mmf_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:t-shirt-2-fill" /></template>
