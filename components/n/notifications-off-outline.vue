<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwk21ob-f.css';
import '../../css/w/wp_6hx3_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mwk21ob-f"/><path class="wp_6hx3_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:notifications-off-outline" /></template>
