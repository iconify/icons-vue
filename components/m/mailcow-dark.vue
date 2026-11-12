<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha0-h7bjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ha0-h7bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mailcow-dark" /></template>
