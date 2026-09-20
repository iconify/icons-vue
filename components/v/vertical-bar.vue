<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfreu8aiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bfreu8aiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:vertical-bar" /></template>
