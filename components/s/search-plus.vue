<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmjay1pmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bmjay1pmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:search-plus" /></template>
