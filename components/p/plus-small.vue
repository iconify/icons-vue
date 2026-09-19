<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyxo40b2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyxo40b2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:plus-small" /></template>
