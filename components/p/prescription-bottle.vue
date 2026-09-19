<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bti3klb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="bti3klb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:prescription-bottle" /></template>
