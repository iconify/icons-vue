<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmii52b6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmii52b6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:user-circle-lock" /></template>
