<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu922hb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gu922hb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netboot-xyz" /></template>
