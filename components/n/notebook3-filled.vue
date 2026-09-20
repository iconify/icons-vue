<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c22_dcbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c22_dcbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:notebook3-filled" /></template>
