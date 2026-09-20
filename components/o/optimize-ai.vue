<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imkjf5qck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imkjf5qck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:optimize-ai" /></template>
