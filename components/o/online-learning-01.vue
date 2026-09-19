<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zstkoeogs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zstkoeogs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:online-learning-01" /></template>
