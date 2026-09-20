<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bck3y324g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bck3y324g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:tag-plus" /></template>
