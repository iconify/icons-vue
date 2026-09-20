<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqj9-4brz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pqj9-4brz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:memorial-stone-with-nine-point-star-outline" /></template>
