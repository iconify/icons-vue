<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k27a35brw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1600,"height":1536};
const content = `<path class="k27a35brw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:thumbs-up" /></template>
