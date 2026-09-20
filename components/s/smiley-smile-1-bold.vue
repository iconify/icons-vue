<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7-2vjb9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7-2vjb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:smiley-smile-1-bold" /></template>
