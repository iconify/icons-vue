<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrd-cjyhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zrd-cjyhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:potable-water-symbol" /></template>
