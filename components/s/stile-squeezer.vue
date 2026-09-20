<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yaszo0-_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yaszo0-_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:stile-squeezer" /></template>
