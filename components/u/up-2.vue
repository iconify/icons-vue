<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/boevr-yxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="boevr-yxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:up-2" /></template>
