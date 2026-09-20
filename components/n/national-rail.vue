<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3qhh86ev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3qhh86ev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:national-rail" /></template>
