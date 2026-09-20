<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj-ns2bmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kj-ns2bmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:projector-screen-outline" /></template>
