<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya-e69b3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ya-e69b3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:swipeup" /></template>
