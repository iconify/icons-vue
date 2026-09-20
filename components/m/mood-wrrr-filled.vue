<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm37cc_9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm37cc_9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:mood-wrrr-filled" /></template>
