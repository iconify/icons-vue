<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nom9670_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nom9670_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:relation-only-one-to-one" /></template>
