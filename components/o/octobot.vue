<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdph_mk2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wdph_mk2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:octobot" /></template>
