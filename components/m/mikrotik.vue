<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynqd7wbwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ynqd7wbwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mikrotik" /></template>
