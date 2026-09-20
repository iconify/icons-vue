<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xeed0tk-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xeed0tk-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:massage" /></template>
