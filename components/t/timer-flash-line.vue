<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doaasx1ge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="doaasx1ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:timer-flash-line" /></template>
