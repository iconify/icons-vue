<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqcm5_b6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqcm5_b6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:redo-24" /></template>
