<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qerf4abpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":512};
const content = `<path class="qerf4abpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:pushed" /></template>
