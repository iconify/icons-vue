<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sndodubfo.css';
import '../../css/a/a4nkfj3oj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sndodubfo"/><path class="a4nkfj3oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:phpsysinfo-dark" /></template>
