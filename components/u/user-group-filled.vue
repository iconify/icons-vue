<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d01p_11kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d01p_11kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-group-filled" /></template>
