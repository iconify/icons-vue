<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvh93qr1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kvh93qr1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:play-circle-filled" /></template>
