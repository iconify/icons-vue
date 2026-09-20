<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akkfssfun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="akkfssfun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:scholarsome-dark" /></template>
