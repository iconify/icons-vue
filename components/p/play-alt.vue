<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgg_xqblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="xgg_xqblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:play-alt" /></template>
