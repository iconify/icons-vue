<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu8hkab6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu8hkab6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:merx-ipc-horizon-dome-alt" /></template>
