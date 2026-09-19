<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1k04xebr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r1k04xebr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:user-unfollow-fill-16" /></template>
