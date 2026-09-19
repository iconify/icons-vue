<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am_zo4ole.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="am_zo4ole"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:scale" /></template>
