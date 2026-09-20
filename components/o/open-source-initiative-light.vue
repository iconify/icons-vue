<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg5_eab7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wg5_eab7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:open-source-initiative-light" /></template>
