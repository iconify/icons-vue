<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz-47q_de.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xz-47q_de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trackly-light" /></template>
