<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnjia1bzi.css';
import '../../css/x/x5gitzbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xnjia1bzi"/><path class="x5gitzbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:microphone-fill-20" /></template>
