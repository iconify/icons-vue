<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn-h0obmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hn-h0obmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:outline-dark" /></template>
