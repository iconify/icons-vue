<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzivp2btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzivp2btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:shrink-diagonal" /></template>
