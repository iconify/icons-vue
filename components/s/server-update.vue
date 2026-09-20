<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epc7_tgau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="epc7_tgau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:server-update" /></template>
