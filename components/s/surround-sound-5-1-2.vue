<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stkdhzbtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stkdhzbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:surround-sound-5-1-2" /></template>
