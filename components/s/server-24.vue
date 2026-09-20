<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpnkqjn8e.css';
import '../../css/i/ifeyr2b5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpnkqjn8e"/><path class="ifeyr2b5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:server-24" /></template>
