<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4eio9bdz.css';
import '../../css/j/j4xpq6z4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4eio9bdz"/><path class="j4xpq6z4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:user" /></template>
