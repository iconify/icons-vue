<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kub96ib8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="kub96ib8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:tray-speech-bubble-26" /></template>
