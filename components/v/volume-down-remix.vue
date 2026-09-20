<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njy1xjbip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="njy1xjbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:volume-down-remix" /></template>
