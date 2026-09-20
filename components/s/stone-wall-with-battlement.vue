<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7arh5b5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t7arh5b5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:stone-wall-with-battlement" /></template>
