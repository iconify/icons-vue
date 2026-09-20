<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk8wbdc9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hk8wbdc9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:redo-16" /></template>
