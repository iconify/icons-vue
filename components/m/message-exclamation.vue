<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6d7q2bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6d7q2bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-exclamation" /></template>
