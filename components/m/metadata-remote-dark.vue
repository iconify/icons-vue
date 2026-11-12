<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn0rtcc5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sn0rtcc5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:metadata-remote-dark" /></template>
