<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6fzf8b3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6fzf8b3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:table-2-fill" /></template>
