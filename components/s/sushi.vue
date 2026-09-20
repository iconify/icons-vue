<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6wah6j7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b6wah6j7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sushi" /></template>
