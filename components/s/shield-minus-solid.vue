<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg24e7-ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pg24e7-ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shield-minus-solid" /></template>
