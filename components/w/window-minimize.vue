<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5a49bwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="xn5a49bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:window-minimize" /></template>
