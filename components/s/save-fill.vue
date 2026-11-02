<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_-i89bqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_-i89bqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:save-fill" /></template>
