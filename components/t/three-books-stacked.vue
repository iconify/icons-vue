<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqybjnb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hqybjnb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:three-books-stacked" /></template>
