<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2u7l2yvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2u7l2yvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:megaphone-outline" /></template>
