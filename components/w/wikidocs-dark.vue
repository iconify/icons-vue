<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckent7btu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ckent7btu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wikidocs-dark" /></template>
