<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x07v6nbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x07v6nbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:warpgate-dark" /></template>
