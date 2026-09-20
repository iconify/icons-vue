<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_po1hivt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e_po1hivt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trek-dark" /></template>
