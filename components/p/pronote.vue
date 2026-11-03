<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twtj5ebts.css';
import '../../css/y/yg0gmx-wy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="twtj5ebts"/><path class="yg0gmx-wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pronote" /></template>
