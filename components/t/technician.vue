<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckj8t0b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckj8t0b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:technician" /></template>
