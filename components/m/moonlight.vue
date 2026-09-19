<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ietc7wbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ietc7wbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:moonlight" /></template>
