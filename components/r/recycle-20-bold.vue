<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq7te71sv.css';
import '../../css/f/fr4uueuzf.css';
import '../../css/w/wgoa5abtu.css';
import '../../css/e/e7r812b2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bq7te71sv"/><path class="fr4uueuzf"/><path class="wgoa5abtu"/><path class="e7r812b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:recycle-20-bold" /></template>
