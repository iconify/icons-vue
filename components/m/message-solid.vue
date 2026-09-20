<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwp_ibcvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rwp_ibcvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:message-solid" /></template>
