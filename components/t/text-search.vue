<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk20wob0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk20wob0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:text-search" /></template>
