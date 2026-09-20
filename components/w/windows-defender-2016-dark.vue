<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4415cjyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l4415cjyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:windows-defender-2016-dark" /></template>
