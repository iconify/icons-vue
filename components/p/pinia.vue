<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcpac4h9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcpac4h9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:pinia" /></template>
