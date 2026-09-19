<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkx8j0z4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lkx8j0z4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:play-fill" /></template>
