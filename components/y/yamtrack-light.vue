<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hclia1bkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hclia1bkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yamtrack-light" /></template>
