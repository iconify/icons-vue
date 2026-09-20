<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eewd2xbxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eewd2xbxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mqtt" /></template>
