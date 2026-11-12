<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixo81-b_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ixo81-b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:planarally-light" /></template>
