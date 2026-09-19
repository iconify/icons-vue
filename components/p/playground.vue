<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqh3ybnie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqh3ybnie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:playground" /></template>
