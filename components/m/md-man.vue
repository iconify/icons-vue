<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5592g8sw.css';
import '../../css/p/pemo8gb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w5592g8sw"/><path class="pemo8gb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-man" /></template>
