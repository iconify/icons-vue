<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_07l1bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_07l1bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-filled" /></template>
