<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzqu9x0yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rzqu9x0yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:patch-exclamation-fill" /></template>
