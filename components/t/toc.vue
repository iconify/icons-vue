<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm22dhbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nm22dhbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:toc" /></template>
