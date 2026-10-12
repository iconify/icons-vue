<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn5j5rbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qn5j5rbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-arrow-right-enter-filled" /></template>
