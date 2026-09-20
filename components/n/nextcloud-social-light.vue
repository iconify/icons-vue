<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl88w1bhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fl88w1bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-social-light" /></template>
