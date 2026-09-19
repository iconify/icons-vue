<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gix87escz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gix87escz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-film" /></template>
