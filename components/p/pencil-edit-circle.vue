<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijywvtboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijywvtboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pencil-edit-circle" /></template>
