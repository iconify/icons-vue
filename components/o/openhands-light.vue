<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8ii04yqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m8ii04yqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openhands-light" /></template>
