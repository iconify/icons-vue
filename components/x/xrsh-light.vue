<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs3-wob5i.css';
import '../../css/a/a3mwubgrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qs3-wob5i"/><path class="a3mwubgrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:xrsh-light" /></template>
