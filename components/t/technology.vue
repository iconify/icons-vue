<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqmmrnbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqmmrnbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:technology" /></template>
