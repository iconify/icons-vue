<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib-0xuzsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ib-0xuzsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:qbittorrent" /></template>
