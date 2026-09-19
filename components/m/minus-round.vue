<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_spqu3na.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w_spqu3na"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:minus-round" /></template>
