<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwd-2zbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lwd-2zbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:user-unfollow-stroke-16" /></template>
