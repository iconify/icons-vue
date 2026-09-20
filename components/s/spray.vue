<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/furm6vb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="furm6vb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:spray" /></template>
