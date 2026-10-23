<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbtmzib3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbtmzib3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:rugby-ball" /></template>
