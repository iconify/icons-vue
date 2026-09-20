<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahla53bhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ahla53bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opentalk-dark" /></template>
