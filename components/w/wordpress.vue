<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh70i435x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mh70i435x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wordpress" /></template>
