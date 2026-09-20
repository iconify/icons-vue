<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu8qm5b8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xu8qm5b8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tooljet-light" /></template>
