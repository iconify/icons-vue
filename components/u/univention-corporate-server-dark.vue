<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-6paieus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z-6paieus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:univention-corporate-server-dark" /></template>
