<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj1embc0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="xj1embc0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:pencil-alt" /></template>
