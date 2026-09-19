<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqp7m7dfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yqp7m7dfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:shield-half-sharp" /></template>
