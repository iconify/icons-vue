<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrihrpbok.css';
import '../../css/q/qrptghg4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":16};
const content = `<path class="vrihrpbok"/><path class="qrptghg4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:youtube2" /></template>
