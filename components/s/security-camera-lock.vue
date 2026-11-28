<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skdqmvxap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skdqmvxap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:security-camera-lock" /></template>
