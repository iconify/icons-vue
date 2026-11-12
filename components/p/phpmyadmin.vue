<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybgh70bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ybgh70bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:phpmyadmin" /></template>
