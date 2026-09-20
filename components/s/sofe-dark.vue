<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn-ou5dst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zn-ou5dst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sofe-dark" /></template>
