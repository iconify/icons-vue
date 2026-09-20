<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxl7tlbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hxl7tlbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:woodpecker-ci-light" /></template>
