<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpsb4mp_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bpsb4mp_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:yin-yang-on-square" /></template>
