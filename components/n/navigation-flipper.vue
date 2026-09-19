<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvujvo0-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="vvujvo0-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:navigation-flipper" /></template>
