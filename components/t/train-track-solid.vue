<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x73e8l8-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x73e8l8-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:train-track-solid" /></template>
