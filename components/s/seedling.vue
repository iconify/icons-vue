<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb5dbo-6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jb5dbo-6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:seedling" /></template>
