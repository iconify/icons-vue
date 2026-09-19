<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe0d824xu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="pe0d824xu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:volume-high" /></template>
