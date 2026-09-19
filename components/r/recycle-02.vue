<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmzwvgbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmzwvgbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:recycle-02" /></template>
