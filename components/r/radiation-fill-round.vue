<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi2hnbb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi2hnbb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:radiation-fill-round" /></template>
