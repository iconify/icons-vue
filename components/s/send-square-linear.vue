<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qcdvqs90r.css';
import '../../css/s/sk3b6qm0n.css';
import '../../css/p/pw8f5c0fp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qcdvqs90r"/><path class="sk3b6qm0n"/><path class="pw8f5c0fp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:send-square-linear" /></template>
