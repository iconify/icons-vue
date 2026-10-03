<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnk3vlb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnk3vlb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:qbittorrent" /></template>
