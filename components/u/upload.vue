<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwtv-rp6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xwtv-rp6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:upload" /></template>
