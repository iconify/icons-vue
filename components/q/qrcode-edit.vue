<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt4p4mb3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt4p4mb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:qrcode-edit" /></template>
