<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8p6quc-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8p6quc-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:mandolin-24" /></template>
