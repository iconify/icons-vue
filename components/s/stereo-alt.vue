<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwyzw-bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwyzw-bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:stereo-alt" /></template>
