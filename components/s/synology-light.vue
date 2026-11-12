<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sozokdb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sozokdb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:synology-light" /></template>
