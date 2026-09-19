<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2jrpnjac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="a2jrpnjac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:pixiv" /></template>
