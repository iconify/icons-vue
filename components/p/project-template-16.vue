<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teorf6boz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="teorf6boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:project-template-16" /></template>
