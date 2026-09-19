<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4406ob8i.css';
import '../../css/y/yg04rqb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i4406ob8i"/><path class="yg04rqb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:right-down" /></template>
