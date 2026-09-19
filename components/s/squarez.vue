<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7q42soot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="x7q42soot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:squarez" /></template>
