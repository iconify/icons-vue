<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzej9cc4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="pzej9cc4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:phone-locked" /></template>
