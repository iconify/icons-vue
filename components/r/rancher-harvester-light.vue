<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-pg133zs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v-pg133zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-harvester-light" /></template>
