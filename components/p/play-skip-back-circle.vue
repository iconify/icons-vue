<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9363gadj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r9363gadj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:play-skip-back-circle" /></template>
