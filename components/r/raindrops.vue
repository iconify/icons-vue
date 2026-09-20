<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phz5pab0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="phz5pab0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:raindrops" /></template>
