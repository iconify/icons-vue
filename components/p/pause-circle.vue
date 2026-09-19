<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1ie9sb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1ie9sb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:pause-circle" /></template>
