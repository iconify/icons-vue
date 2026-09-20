<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/goaywzbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="goaywzbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:minarca-light" /></template>
