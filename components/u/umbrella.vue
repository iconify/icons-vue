<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr2ui3bao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="nr2ui3bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:umbrella" /></template>
