<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evixo2yul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evixo2yul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:reply-all-bulk-round" /></template>
