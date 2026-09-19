<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axuv2sb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="axuv2sb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:play-circle-sharp" /></template>
