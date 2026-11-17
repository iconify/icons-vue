<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivd6g4r7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ivd6g4r7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rasputin-management" /></template>
