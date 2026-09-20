<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1m7o-bav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="d1m7o-bav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:runtime-settings" /></template>
