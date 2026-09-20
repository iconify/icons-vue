<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/beoeifunj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="beoeifunj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:map-direction" /></template>
