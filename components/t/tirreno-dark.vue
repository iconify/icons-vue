<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygo7n3bmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ygo7n3bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tirreno-dark" /></template>
