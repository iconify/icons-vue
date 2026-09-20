<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoqu0cb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xoqu0cb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nutalert-light" /></template>
