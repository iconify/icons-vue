<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa8hv5m4d.css';
import '../../css/x/xn18y8bul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pa8hv5m4d"/><rect class="xn18y8bul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:margin-top-filled" /></template>
