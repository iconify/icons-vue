<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moa8elbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="moa8elbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:star-plus-alt" /></template>
