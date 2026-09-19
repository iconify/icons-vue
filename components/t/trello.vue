<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt82mz-wp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="tt82mz-wp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:trello" /></template>
