<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg7oumb9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fg7oumb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rectangle-vertical-fill" /></template>
