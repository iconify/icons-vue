<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szbk04d_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="szbk04d_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:scrob-light" /></template>
