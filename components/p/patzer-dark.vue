<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd_7uwjfj.css';
import '../../css/h/h9qt_bcyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gd_7uwjfj"/><path class="h9qt_bcyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:patzer-dark" /></template>
