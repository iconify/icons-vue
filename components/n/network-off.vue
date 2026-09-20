<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrlhhbb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrlhhbb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:network-off" /></template>
