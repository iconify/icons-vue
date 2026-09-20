<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw2pvlb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yw2pvlb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:move-up-outline" /></template>
