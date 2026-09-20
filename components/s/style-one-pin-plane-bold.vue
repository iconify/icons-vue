<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hym10un3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hym10un3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:style-one-pin-plane-bold" /></template>
