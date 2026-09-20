<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyxb3qb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyxb3qb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-backward-5-fill" /></template>
