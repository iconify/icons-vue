<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xri0ftdmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xri0ftdmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:underline" /></template>
