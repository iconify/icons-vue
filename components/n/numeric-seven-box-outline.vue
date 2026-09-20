<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s00hep_zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s00hep_zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-seven-box-outline" /></template>
