<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9tlc311j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j9tlc311j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tag-with-euro" /></template>
