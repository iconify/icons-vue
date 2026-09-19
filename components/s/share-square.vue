<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6b1et9wp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="b6b1et9wp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:share-square" /></template>
