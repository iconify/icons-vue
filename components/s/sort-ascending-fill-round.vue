<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye8mq4bhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye8mq4bhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sort-ascending-fill-round" /></template>
