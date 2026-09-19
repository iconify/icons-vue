<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe0j13bar.css';
import '../../css/y/y7bs-t6_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe0j13bar"/><path class="y7bs-t6_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:microphone" /></template>
