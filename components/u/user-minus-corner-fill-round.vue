<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ced08nb-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ced08nb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-minus-corner-fill-round" /></template>
