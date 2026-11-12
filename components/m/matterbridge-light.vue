<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfc6_nbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hfc6_nbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:matterbridge-light" /></template>
