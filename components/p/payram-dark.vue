<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spuyad3fw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="spuyad3fw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:payram-dark" /></template>
