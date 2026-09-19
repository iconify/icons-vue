<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_0v-4byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u_0v-4byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:universal-access" /></template>
