<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6plfozmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6plfozmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:one-square-solid" /></template>
