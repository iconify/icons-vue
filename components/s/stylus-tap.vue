<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqet34bfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wqet34bfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:stylus-tap" /></template>
