<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li4g1kbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="li4g1kbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:point-down" /></template>
