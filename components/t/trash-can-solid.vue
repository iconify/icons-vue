<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lysg2jqtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lysg2jqtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:trash-can-solid" /></template>
