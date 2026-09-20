<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcx89nbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rcx89nbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:turnkey-linux-dark" /></template>
