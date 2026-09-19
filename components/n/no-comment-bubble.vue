<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3m_nk0lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1664};
const content = `<path class="n3m_nk0lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:no-comment-bubble" /></template>
