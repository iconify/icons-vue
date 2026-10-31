<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxh3qji2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qxh3qji2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:paint-brush-slash-16-solid" /></template>
