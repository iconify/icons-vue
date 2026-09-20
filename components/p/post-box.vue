<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqe_5emhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hqe_5emhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:post-box" /></template>
