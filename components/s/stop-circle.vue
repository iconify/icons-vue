<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw0uhdchi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sw0uhdchi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:stop-circle" /></template>
