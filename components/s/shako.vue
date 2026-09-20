<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugz90_-pi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ugz90_-pi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:shako" /></template>
