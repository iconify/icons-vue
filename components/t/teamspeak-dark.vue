<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yurvowxon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yurvowxon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:teamspeak-dark" /></template>
