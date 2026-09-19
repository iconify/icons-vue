<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-iumubbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-iumubbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:reolink-doorbell" /></template>
