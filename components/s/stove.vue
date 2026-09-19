<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnx3ggb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="cnx3ggb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:stove" /></template>
