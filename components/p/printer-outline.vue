<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihkre-bnx.css';
import '../../css/v/v7i0-vbmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihkre-bnx"/><path clip-rule="evenodd" class="v7i0-vbmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:printer-outline" /></template>
