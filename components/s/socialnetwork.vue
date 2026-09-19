<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuazwe1im.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wuazwe1im"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:socialnetwork" /></template>
