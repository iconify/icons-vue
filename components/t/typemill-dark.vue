<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gugv25bse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gugv25bse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:typemill-dark" /></template>
