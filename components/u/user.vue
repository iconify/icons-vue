<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssoqd4bjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ssoqd4bjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:user" /></template>
