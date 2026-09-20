<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr9_a__7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qr9_a__7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:palette2" /></template>
