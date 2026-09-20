<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i64rjbc9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i64rjbc9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:moai-fill" /></template>
