<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwhv-n0jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="fwhv-n0jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:stop-outline" /></template>
