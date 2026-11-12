<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymi_3kb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ymi_3kb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloudpi-light" /></template>
