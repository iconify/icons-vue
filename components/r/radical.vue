<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrq5u1bco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrq5u1bco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:radical" /></template>
