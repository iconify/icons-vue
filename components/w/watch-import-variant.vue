<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms5m7db0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ms5m7db0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:watch-import-variant" /></template>
