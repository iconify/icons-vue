<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb4rv0hxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jb4rv0hxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:uploading-filled" /></template>
