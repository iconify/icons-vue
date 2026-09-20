<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd8eg6pwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jd8eg6pwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:pause-circle-o" /></template>
