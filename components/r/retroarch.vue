<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjbqnzb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjbqnzb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:retroarch" /></template>
