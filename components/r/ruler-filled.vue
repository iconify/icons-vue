<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycmdnnb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycmdnnb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:ruler-filled" /></template>
