<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd5pzlbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fd5pzlbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:thumbs-down-fill-20" /></template>
