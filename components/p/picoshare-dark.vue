<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn4u02bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nn4u02bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:picoshare-dark" /></template>
