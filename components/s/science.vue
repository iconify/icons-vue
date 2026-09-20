<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogv1gbb3q.css';
import '../../css/x/xp-jb6vzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogv1gbb3q"/><path class="xp-jb6vzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:science" /></template>
