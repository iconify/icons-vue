<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqinukb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xqinukb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:security-camera" /></template>
