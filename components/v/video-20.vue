<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9d68gmeo.css';
import '../../css/z/zuvofvbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u9d68gmeo"/><path class="zuvofvbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:video-20" /></template>
