<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi-u46bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi-u46bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:xtz-fill" /></template>
