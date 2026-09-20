<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e78tupbmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e78tupbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-teams-2018-dark" /></template>
