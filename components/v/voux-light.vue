<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkh7o7b5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vkh7o7b5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:voux-light" /></template>
