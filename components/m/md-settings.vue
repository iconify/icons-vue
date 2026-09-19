<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkx1mt1bx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rkx1mt1bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-settings" /></template>
