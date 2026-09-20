<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqxuq9btg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqxuq9btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:signal-cellular-off-line" /></template>
