<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urm15cc8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="urm15cc8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-alt-new" /></template>
