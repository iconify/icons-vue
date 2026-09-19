<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmwflr6ov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dmwflr6ov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:share-alternitive" /></template>
