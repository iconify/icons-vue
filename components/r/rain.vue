<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlg7xccoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlg7xccoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:rain" /></template>
