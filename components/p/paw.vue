<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjvc_dj1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xjvc_dj1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:paw" /></template>
