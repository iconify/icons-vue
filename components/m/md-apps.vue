<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7u9rlhtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l7u9rlhtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-apps" /></template>
