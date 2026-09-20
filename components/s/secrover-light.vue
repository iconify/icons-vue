<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcnnylysu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jcnnylysu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:secrover-light" /></template>
