<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbdhombsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbdhombsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sonos-era-100" /></template>
