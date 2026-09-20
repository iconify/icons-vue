<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh4zwjb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dh4zwjb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-sharepoint-2013-light" /></template>
