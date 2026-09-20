<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmkn8zbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xmkn8zbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:move-outline" /></template>
