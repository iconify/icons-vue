<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eee5vqkqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eee5vqkqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:trademark" /></template>
