<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5nlddckh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v5nlddckh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:palo-alto-networks-dark" /></template>
