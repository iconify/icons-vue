<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkgd5826b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkgd5826b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sonos" /></template>
