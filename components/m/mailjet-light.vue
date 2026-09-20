<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6a744bif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o6a744bif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mailjet-light" /></template>
