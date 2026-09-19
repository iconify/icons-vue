<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osur7d7zf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="osur7d7zf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:reload-fill-16" /></template>
