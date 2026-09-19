<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl_82zymi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl_82zymi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:more-vertical-circle-01" /></template>
