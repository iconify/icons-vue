<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj348nt0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj348nt0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:near-field-communication-tap" /></template>
