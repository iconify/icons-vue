<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it48t2bjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="it48t2bjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:rightangerbubble" /></template>
