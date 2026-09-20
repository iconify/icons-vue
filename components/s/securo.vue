<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss1_jtd_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ss1_jtd_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:securo" /></template>
