<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5a44_ban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f5a44_ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-outlook-2018-dark" /></template>
