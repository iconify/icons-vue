<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymq0d1b4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymq0d1b4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:rss" /></template>
