<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymlejsi7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ymlejsi7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:reload-circle-sharp" /></template>
