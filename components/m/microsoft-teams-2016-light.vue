<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db_3tsw-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="db_3tsw-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-teams-2016-light" /></template>
