<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y55np039p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y55np039p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:pause" /></template>
