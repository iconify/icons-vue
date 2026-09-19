<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wkm6c6j9i.css';
import '../../css/d/dkfqmgbcg.css';
import '../../css/z/zlkcfkcwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wkm6c6j9i"/><path class="dkfqmgbcg"/><path class="zlkcfkcwp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:money-send-circle" /></template>
