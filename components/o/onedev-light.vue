<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvj0q6bsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dvj0q6bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:onedev-light" /></template>
