<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td6rwibok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td6rwibok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:target-fill" /></template>
