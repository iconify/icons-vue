<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugqf-vbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ugqf-vbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:save-outline" /></template>
