<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd4fpfb_f.css';
import '../../css/b/b337xtreo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="fd4fpfb_f"/><path class="b337xtreo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:page-doc" /></template>
