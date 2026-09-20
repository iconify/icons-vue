<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k07pw1b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="k07pw1b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:night-snow" /></template>
