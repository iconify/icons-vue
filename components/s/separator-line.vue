<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyiv34bjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="jyiv34bjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:separator-line" /></template>
