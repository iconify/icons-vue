<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymmm_yblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ymmm_yblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-snow" /></template>
