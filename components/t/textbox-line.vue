<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r39k3lb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r39k3lb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:textbox-line" /></template>
