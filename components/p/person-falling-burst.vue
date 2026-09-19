<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1a-lobmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="r1a-lobmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:person-falling-burst" /></template>
