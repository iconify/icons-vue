<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k63gv6hoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k63gv6hoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:transfer-horizontal-line" /></template>
