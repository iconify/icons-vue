<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypi9hb3rc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ypi9hb3rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:neutral-face" /></template>
