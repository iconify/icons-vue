<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akjnrbb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="akjnrbb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:sort" /></template>
