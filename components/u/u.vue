<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k82mb-blf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":769,"height":1024};
const content = `<path class="k82mb-blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:u" /></template>
