<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1e3i_olm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e1e3i_olm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:step-ca" /></template>
