<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai18v7u3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ai18v7u3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:truck-filled" /></template>
