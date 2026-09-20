<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg94oxbop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rg94oxbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:plug-socket-eu" /></template>
