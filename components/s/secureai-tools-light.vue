<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfg2xib9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pfg2xib9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:secureai-tools-light" /></template>
