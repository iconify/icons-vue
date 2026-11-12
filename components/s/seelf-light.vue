<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yil0imbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yil0imbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:seelf-light" /></template>
