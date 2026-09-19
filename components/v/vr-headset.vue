<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rawn7f28d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rawn7f28d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:vr-headset" /></template>
