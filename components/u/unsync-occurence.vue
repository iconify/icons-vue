<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsaw33-sj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zsaw33-sj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:unsync-occurence" /></template>
