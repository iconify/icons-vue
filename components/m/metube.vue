<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1_zu51bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j1_zu51bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:metube" /></template>
