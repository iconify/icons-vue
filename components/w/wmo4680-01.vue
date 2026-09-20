<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhc8dieas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="bhc8dieas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:wmo4680-01" /></template>
