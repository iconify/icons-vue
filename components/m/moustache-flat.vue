<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrax7kfye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="qrax7kfye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:moustache-flat" /></template>
