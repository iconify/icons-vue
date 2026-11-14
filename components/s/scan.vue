<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzlcfmbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzlcfmbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:scan" /></template>
