<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqo-pac3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vqo-pac3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pixelfin-light" /></template>
