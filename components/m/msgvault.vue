<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rod24kbrj.css';
import '../../css/y/y20r2pbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rod24kbrj"/><path class="y20r2pbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:msgvault" /></template>
