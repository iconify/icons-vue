<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8ngi2bsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m8ngi2bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nginx-proxy-manager-dark" /></template>
