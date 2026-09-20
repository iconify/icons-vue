<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yslno4_-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yslno4_-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tirreno-light" /></template>
