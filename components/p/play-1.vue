<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa4ivzb0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oa4ivzb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:play-1" /></template>
