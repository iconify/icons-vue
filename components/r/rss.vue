<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq82kuboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tq82kuboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:rss" /></template>
