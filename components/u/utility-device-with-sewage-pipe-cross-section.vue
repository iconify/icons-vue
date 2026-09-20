<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_dkf0bpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z_dkf0bpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:utility-device-with-sewage-pipe-cross-section" /></template>
