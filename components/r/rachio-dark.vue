<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpmf_dl3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wpmf_dl3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rachio-dark" /></template>
