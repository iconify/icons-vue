<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm_5ox-rc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fm_5ox-rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:patchmon-light" /></template>
