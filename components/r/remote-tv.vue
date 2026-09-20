<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfz4o-m7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfz4o-m7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:remote-tv" /></template>
