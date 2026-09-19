<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvs3kpobq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yvs3kpobq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:user-circle-fill-16" /></template>
