<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2tai9bqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a2tai9bqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:virus-filled" /></template>
