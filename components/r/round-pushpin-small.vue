<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn64bt0bj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="wn64bt0bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:round-pushpin-small" /></template>
