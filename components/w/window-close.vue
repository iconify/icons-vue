<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0m-qub2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0m-qub2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:window-close" /></template>
