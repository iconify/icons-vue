<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq903rb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sq903rb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:parking" /></template>
