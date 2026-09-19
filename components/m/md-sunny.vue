<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot5kipbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ot5kipbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-sunny" /></template>
