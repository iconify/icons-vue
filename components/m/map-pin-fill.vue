<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x04u6rb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x04u6rb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:map-pin-fill" /></template>
