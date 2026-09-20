<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_wce6bqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_wce6bqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:volume-minus" /></template>
