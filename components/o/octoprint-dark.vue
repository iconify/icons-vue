<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4wet1bse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s4wet1bse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:octoprint-dark" /></template>
