<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqh9pub3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqh9pub3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-landing-side-fill-round" /></template>
