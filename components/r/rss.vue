<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/poj4ron-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="poj4ron-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:rss" /></template>
