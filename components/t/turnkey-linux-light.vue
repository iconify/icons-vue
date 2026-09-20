<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq5q6vrgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vq5q6vrgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:turnkey-linux-light" /></template>
