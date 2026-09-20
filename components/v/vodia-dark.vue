<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh90gerbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sh90gerbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vodia-dark" /></template>
