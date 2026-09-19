<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm7jd5bvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rm7jd5bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:usa-flag" /></template>
