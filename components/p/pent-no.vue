<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfc-mjbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hfc-mjbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pent-no" /></template>
