<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxveumuww.css';
import '../../css/d/dekf_bboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wxveumuww"/><path class="dekf_bboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:reply-all-16" /></template>
