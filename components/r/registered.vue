<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3pyio9mi.css';
import '../../css/s/s9qx38vbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3pyio9mi"/><path class="s9qx38vbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:registered" /></template>
