<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbycz7_ya.css';
import '../../css/h/hueeqab-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xbycz7_ya"/><circle class="hueeqab-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:pulse-outline" /></template>
