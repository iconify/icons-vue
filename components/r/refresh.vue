<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of-adsbxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":631,"height":718};
const content = `<path class="of-adsbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:refresh" /></template>
