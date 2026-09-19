<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsit20tsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsit20tsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sonos-era-300" /></template>
