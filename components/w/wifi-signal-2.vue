<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p95zaibmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p95zaibmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:wifi-signal-2" /></template>
