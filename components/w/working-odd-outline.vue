<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qirq4acbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qirq4acbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:working-odd-outline" /></template>
