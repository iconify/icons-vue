<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1qw3obyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1qw3obyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:ranking-stars-ribbon-bold" /></template>
