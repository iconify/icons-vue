<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz7rj6bxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bz7rj6bxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rabbit-fill-round" /></template>
