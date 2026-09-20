<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucefltb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucefltb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:man" /></template>
