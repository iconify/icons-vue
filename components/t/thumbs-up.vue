<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gugcfebgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gugcfebgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:thumbs-up" /></template>
