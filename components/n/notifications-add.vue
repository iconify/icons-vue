<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqc52gbkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":456};
const content = `<path class="uqc52gbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:notifications-add" /></template>
