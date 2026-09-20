<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmg0r4s3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vmg0r4s3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:pictures-folder-memories-remix" /></template>
