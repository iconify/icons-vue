<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkti_bbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkti_bbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:popcorn" /></template>
