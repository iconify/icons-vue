<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haz-qe35l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="haz-qe35l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:uiw" /></template>
