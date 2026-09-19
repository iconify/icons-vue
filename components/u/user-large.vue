<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldnn-kber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ldnn-kber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:user-large" /></template>
