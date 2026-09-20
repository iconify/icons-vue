<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2p5fcbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f2p5fcbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zoho-mail-light" /></template>
