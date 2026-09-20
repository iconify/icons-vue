<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5zx9_4id.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d5zx9_4id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:shield" /></template>
