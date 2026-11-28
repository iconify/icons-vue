<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4784_7qf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4784_7qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:monitor-cog-solid" /></template>
