<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms0ln98en.css';
import '../../css/i/i3opoge7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ms0ln98en"/><path class="i3opoge7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:quire-ink-light" /></template>
