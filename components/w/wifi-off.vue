<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd6pj_b9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jd6pj_b9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:wifi-off" /></template>
