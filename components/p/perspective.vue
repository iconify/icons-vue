<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrcxmmh5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zrcxmmh5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:perspective" /></template>
