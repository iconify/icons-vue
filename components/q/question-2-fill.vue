<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgkvktvjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgkvktvjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:question-2-fill" /></template>
