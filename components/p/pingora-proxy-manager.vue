<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czfhl0lnw.css';
import '../../css/f/f4wrckbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="czfhl0lnw"/><path class="f4wrckbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pingora-proxy-manager" /></template>
