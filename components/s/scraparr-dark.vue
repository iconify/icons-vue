<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhr8y1ueq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uhr8y1ueq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:scraparr-dark" /></template>
