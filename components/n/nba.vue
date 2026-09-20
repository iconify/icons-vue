<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy0k6tbhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cy0k6tbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:nba" /></template>
