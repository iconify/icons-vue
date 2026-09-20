<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srb-b2b2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srb-b2b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:snapchat-alt" /></template>
