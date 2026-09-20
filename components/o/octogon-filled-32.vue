<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j73-s3h3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j73-s3h3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:octogon-filled-32" /></template>
