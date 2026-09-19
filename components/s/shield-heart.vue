<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds2fcdn8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ds2fcdn8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:shield-heart" /></template>
