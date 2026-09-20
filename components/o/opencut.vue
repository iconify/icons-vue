<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x23666r1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x23666r1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opencut" /></template>
