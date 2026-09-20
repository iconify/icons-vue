<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we21v81ge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="we21v81ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:shortcode" /></template>
