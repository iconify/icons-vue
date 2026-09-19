<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo14_sr-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bo14_sr-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:menu-fill-16" /></template>
