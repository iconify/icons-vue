<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q83fie9rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q83fie9rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:user-square-fill" /></template>
