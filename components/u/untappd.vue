<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfvlv_bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wfvlv_bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:untappd" /></template>
