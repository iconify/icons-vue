<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm3tpvt0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm3tpvt0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:scan-helper" /></template>
