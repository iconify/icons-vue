<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uszf_sena.css';
import '../../css/w/wzdcrsbth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uszf_sena"/><path class="wzdcrsbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mail-unread-20" /></template>
