<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwwsb4kdp.css';
import '../../css/y/ylvsggrtp.css';
import '../../css/m/mj3qn8bcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="lwwsb4kdp"/><path class="ylvsggrtp"/><path class="mj3qn8bcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mitmproxy" /></template>
