<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsgw1ybqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsgw1ybqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:miniplayer-fill" /></template>
