<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jca3u64_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jca3u64_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:signpost" /></template>
