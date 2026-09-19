<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7260r08q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="b7260r08q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:pinterest" /></template>
