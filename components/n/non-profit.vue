<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g69w9nb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g69w9nb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:non-profit" /></template>
