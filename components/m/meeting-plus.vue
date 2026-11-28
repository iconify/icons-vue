<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_q3-0bak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_q3-0bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:meeting-plus" /></template>
