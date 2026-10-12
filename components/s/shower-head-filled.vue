<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owfrw6bin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owfrw6bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shower-head-filled" /></template>
