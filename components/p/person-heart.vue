<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quicy360w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="quicy360w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:person-heart" /></template>
