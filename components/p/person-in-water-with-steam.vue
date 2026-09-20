<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orqlr3bbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="orqlr3bbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-in-water-with-steam" /></template>
