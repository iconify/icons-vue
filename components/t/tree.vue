<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo0ac2boh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jo0ac2boh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:tree" /></template>
