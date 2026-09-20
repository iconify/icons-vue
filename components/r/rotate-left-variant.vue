<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdisb8b-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdisb8b-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rotate-left-variant" /></template>
