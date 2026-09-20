<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3k6m-bgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v3k6m-bgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-sharepoint-light" /></template>
