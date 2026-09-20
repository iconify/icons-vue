<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1kuotbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f1kuotbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tautulli-light" /></template>
