<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oun4-vbvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oun4-vbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:person-cancel" /></template>
