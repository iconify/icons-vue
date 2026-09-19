<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvya9l6dj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mvya9l6dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:sort-one" /></template>
