<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa2yz5sit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":470,"height":512};
const content = `<path class="wa2yz5sit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:tilt" /></template>
