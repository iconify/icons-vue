<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt7c5vbnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="xt7c5vbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:site-logo" /></template>
