<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oesco-xxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oesco-xxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pushover-light" /></template>
