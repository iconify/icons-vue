<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7h3bczat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p7h3bczat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:x-fill-16" /></template>
