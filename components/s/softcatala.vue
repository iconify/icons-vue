<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yprqjz2uq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yprqjz2uq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:softcatala" /></template>
