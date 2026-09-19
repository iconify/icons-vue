<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xem2oro9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xem2oro9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:paper-plane" /></template>
