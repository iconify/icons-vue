<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx1ln9b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qx1ln9b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:romarr-light" /></template>
