<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je7ygt42x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je7ygt42x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:whiteboard" /></template>
