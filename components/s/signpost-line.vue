<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z48zn0bsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z48zn0bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:signpost-line" /></template>
