<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj2bkebcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mj2bkebcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:openai" /></template>
