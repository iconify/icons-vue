<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpfxdab7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hpfxdab7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:minecraft" /></template>
