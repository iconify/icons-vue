<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja084uz5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ja084uz5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:notebook" /></template>
