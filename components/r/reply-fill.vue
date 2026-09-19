<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-ng6dyja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h-ng6dyja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:reply-fill" /></template>
