<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2ig19obm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j2ig19obm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-hand" /></template>
