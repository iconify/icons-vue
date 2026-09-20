<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw12ul06r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="uw12ul06r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:plant-details-filled" /></template>
