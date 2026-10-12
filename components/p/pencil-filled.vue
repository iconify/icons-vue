<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7482vbaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7482vbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:pencil-filled" /></template>
