<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flgm55cub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flgm55cub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:space-ship-line" /></template>
