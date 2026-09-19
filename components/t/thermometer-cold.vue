<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sal356e5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sal356e5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:thermometer-cold" /></template>
