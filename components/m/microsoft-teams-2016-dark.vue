<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qym-qrooz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qym-qrooz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-teams-2016-dark" /></template>
