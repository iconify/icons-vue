<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdpj7wl7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdpj7wl7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:numbers" /></template>
