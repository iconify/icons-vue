<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyfb9dbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="fyfb9dbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:white-medium-star-small" /></template>
