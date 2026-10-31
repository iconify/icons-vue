<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzlj2ol0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzlj2ol0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:option-fill-round" /></template>
