<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymbcvd2tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ymbcvd2tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:spip" /></template>
