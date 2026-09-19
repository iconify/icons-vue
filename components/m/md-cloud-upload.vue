<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwxtu6bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xwxtu6bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-cloud-upload" /></template>
