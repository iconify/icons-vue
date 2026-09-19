<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p160bbc6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="p160bbc6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:share-alt-square" /></template>
